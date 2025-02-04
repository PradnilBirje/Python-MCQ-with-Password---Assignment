# Python-MCQ-with-Password---Assignment

###Question
```Set your password :
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
   
   Select Answer 2 ... con..```

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
        print("correct Answer...Con...")
    else:
        print("Wrong Answer, Try next year")```
