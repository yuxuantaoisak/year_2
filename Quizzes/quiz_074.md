## Paper work

![98](https://github.com/user-attachments/assets/5debaaa6-089c-4c6c-8c54-07ae8d6ff901)


## Code

```.py

def error_detector(msg):
    parity = msg[0]
    count = 0
    for i in range(1, len(msg)):
        if msg[i] == "1":
            count += 1
    if count % 2 == 0 and parity == "1":
        return "Error free"
    elif count % 2 == 1 and parity == "0":
        return "Error free"
    else:
        return "Error detected"


print(error_detector("101110110"))
print(error_detector("011101111101110111110111001111"))

```

## Proof of work

<img width="1031" alt="Screenshot 2024-09-10 at 14 01 42" src="https://github.com/user-attachments/assets/de3b61ce-8b96-4972-922c-a9b15c45b6f5">
