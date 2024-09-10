## Paper work

![207_0](https://github.com/user-attachments/assets/b8973253-84aa-4513-9e82-5b15d099bb58)

![208_0](https://github.com/user-attachments/assets/e88ef67b-d86e-4f55-97e1-e450068001fd)

## Code

```.py
def function(lst: list):
    if len(lst) == 1:
        return lst[0]
    m = function(lst[1:])
    if lst[0] > m:
        return lst[0]
    else:
        return m


print(function([3, 1, 8, 7]))

```

## Proof of work

![Screenshot 2024-09-10 at 23 28 46](https://github.com/user-attachments/assets/fc67831e-fc59-45b4-8c08-46a98c8f05b2)
