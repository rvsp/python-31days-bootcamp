1. From the below dictionary, print the `items and roles`

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
2. What is the output?

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
3. From the below snippet print the `match`

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
