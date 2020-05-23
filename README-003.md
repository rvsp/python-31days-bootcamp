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


5. What is output for below code?

    ```python
    def sample():
        value = 10
        def sample1():
            value1=20
            print(value)
        sample1()
        print(value1)

    sample()
    ```

    ```python
    def sample():
        value = 10
        def sample1():
            global value1
            value1=20
            print(value)
        sample1()
        print(value1)

    sample()
    ```
    ---------------------------------------

6. What is output?

    ```python
    def outer():
        x = "local"
        def inner():
            nonlocal x
            # nonlocal x
            x = "nonlocal"
            print("inner:", x)
        inner()
        print("outer:", x)
    outer()
    ```
    ---------------------------------------