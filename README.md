# Python-MCQ-with-Password---Assignment

```This project is a simple Java-based MCQ exam simulation with a password authentication system. 
The program ensures that the user enters the correct password before starting the exam. 
If the user enters the wrong password three times, they are locked out. 
Once authenticated, the program presents multiple-choice questions and evaluates the user's responses.

Features
   Password Authentication: The user must enter the correct password to start the exam.
   Limited Attempts: The user gets three attempts to enter the correct password.
   MCQ Exam: The system presents multiple-choice questions one by one.
   Validation: If the user selects the correct answer, they proceed to the next question; otherwise, they are disqualified.

Example Flow
Password Entry
   User sets the password: p4n@in
   User enters incorrect passwords: p4n, p4n@, p4n@34
   If all three attempts fail, access is denied.
   If the correct password is entered, the MCQ exam begins.

MCQ Exam

Question 1: Who invented Java Programming?

Guido van Rossum
James Gosling
Dennis Ritchie
Bjarne Stroustrup
User selects option 2 (Correct answer: James Gosling).

If correct, move to the next question; if incorrect, they must retry next year.

Question 2: Which component is used to compile, debug, and execute Java programs?

JRE
JIT
JDK
JVM
User selects option 2 (Incorrect answer).

If the answer is correct, the next question appears; otherwise, the exam ends.

###Question
   Set your password :
   p4n@in
   Enter your Password : 
   p4n
   wrong password ... try 2 more time out of 2
   p4n@
   wrong password ... try 1 more time 1
   p4n@34
   wrong password ... try 0 more time 0
   note : user select right password
   then start MCQ EXAM...
   
    
   1. Who invented Java Programming?
   1. ) Guido van Rossum
   2. ) James Gosling
   3. ) Dennis Ritchie
   4. ) Bjarne Stroustrup
   
   Select Answer 2
   
   wrong answer [ Try Next year ] 
   
   Note :if select Right Answer 
   ask 2nd Question ...
   
   2. Which component is used to compile, debug and execute the java programs?
   1. ) JRE
   2. ) JIT
   3. ) JDK
   4. ) JVM
   
   Select Answer 2 ... con..

###Solution

```Password = "Pradnil@45"
Entered_password = input("Enter your Password:")
if Entered_password == Password:
    print("start MCQ EXAM")
else:
    print("wrong password...try 2 more times out of 2")
    
    Entered_password = input("Enter your Password:")
    
    if Entered_password == Password:
        print("start MCQ EXAM")
    else:
        print("wrong password...try 1 more times out of 1")

        Entered_password = input("Enter your Password:")
    
        if Entered_password == Password:
            print("start MCQ EXAM")
        else:
            print("wrong password...try next year")

if Entered_password == Password:
    print("n\1. who invented java Programming")
    print("     1.)Guido van Rossum")
    print("     2.)james Gosling")
    print("     3.)Dennis Ritchie")
    print("     4.)Bjarne Stroustrup")
    Typed_Answered = input("select your answer (1/2/3/4):")

    if Typed_Answered == "2":
        print("correct Answer")
    else:
        print("Wrong Answer, Try next year")
if Typed_Answered == "2":
    print("n\1. which component is used to compile, debug and execute the java programs")
    print("     1.)JRE")
    print("     2.)JIT")
    print("     3.)JDK")
    print("     4.)jvm")
    Typed_Answered = input("select your answer (1/2/3/4):")

    if Typed_Answered == "2":
        print("correct Answer...Con...")```
    else:
        print("Wrong Answer, Try next year")```
