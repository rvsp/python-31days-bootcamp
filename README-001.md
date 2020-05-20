# Python-31Days-Bootcamp

## Day-01

1. What is the result of below snippet?

    ``` python
        list_1 = [1, 2, 3]
        list_2 = [1, 2, 3]
        print(list_1 == list_2)
        print(list_1 is list_2)
    ```

    ---------------------------------------
2. Write a python code to count no. of starting letter of capital words in each line.

    ``` output
        Line-1: 3
        Line-2: 10
    ```

    ---------------------------------------
3. Predict the output for the below code.

    ``` python
        iterator = (i for i in range(1, 4))
        matrix = [[x * y for y in iterator] for x in iterator]
        print(matrix)
    ```

    ---------------------------------------
4. What is the output for below code? justify your answer

    ``` python
        def extendList(val, list=[]):
            list.append(val)
            return list

        list1 = extendList(10)
        list2 = extendList(123,[])
        list3 = extendList('a')

        print ("list1 = %s" % list1)
        print ("list2 = %s" % list2)
        print ("list3 = %s" % list3)
    ```

    ---------------------------------------

5. From the below list, write python code to sum only the year from date of birth

    ```python
    userData = [
        ["0001", "Roman Alamsyah", "Bandar Lampung", "21/05/1989", "Membaca"],
        ["0002", "Dika Sembiring", "Medan", "10/10/1992", "Bermain Gitar"], 
        ["0003", "Winona", "Ambon", "25/12/1965", "Memasak"], 
        ["0004", "Bintang Senjaya", "Martapura", "6/4/1970", "Berkebun"]
    ]
    ```

    ---------------------------------------

6. Justify the Difference below snippets.

    ``` python
        letter = "hai sethuraman"
        for i in letter:
            if i == "a":
                pass
                print("pass statement")
            else:
                print(i)
    ```

    ``` python
        letter = "hai sethuraman"
        for i in letter:
            if i == "a":
                continue
                print("continue statement")
            else:
                print(i)
    ```
    ---------------------------------------
