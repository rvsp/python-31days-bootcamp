1. Write a function which has ability to accept `*N` arguments.

    ---------------------------------------

2. What is difference between below two codes.

    ``` python
        def myFunc(*argList):  
            for argx in argList:  
                print (argx) 
            
        myFunc('I', 'am', 'Learning', 'Python')
    ```

    ``` python
        def myFunc1(arg1, arg2, arg3, arg4):
                print(arg1, arg2, arg3, arg4)
            
        myFunc1('I', 'am', 'Learning', 'Python')
    ```

    ---------------------------------------

3. What does the `**kwargs` do in Python? Explain with below snippet.

    ``` python
        def myFuncArgs(**kwargs):
            for emp, age in kwargs.items():
                print ("%s's age is %s." %(emp, age))
            
        myFuncArgs(John=25, Kalley=22, Tom=32)
    ```

    ---------------------------------------

4. Explain the below snippet

    ``` python
    def A(x):
        print('outer function')
        print(x)
        def B():
            x=20
            print('inner function')
            print(x)
        return B
        print('Exit')

    A(7)()
    ```
    ---------------------------------------