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

5. From the below dictionary, print the `items and roles`

    ```python
    junk = {
        "characters": {
            "Lonestar": {
                "id": 55923,
                "role": "renegade",
                "items": [
                    "space winnebago",
                    "leather jacket"
                ]
            },
            "Barfolomew": {
                "id": 55924,
                "role": "mawg",
                "items": [
                    "peanut butter jar",
                    "waggy tail"
                ]
            },
            "Dark Helmet": {
                "id": 99999,
                "role": "Good is dumb",
                "items": [
                    "Shwartz",
                    "helmet"
                ]
            },
            "Skroob": {
                "id": 12345,
                "role": "Spaceballs CEO",
                "items": [
                    "luggage"
                ]
            }
        }
    }
    ```

---------------------------------------
6. What is the output?

    ```python
    a = [1,2,3]
    a[0] = 0
    a[1] = 1
    a[2] = 2

    i=0

    while (i<3):
        a[i] = 1
        i+=1
        
    print(a)
    ```

---------------------------------------
7. From the below snippet print the `mats`

    ```python
    body = {
        'query': {
            'filtered': {
                'query': {
                    'match': {'description': 'addictive'}
                },
                'filter': {
                    'term': {'created_by': 'Mats'}
                }
            }
        }
    }
    ```

    ---------------------------------------

8. What is output for below code?

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

9. What is output?

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