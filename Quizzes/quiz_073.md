## Paper work

![100](https://github.com/user-attachments/assets/0aa2b388-a8d3-4c64-bb18-6032175fe1d8)

## Code

```.py

def data_correction(data):
    size = int(len(data) / 3)
    first = ""
    for i in range(size):
        first += data[i]
    second = ""
    for i in range(size, size*2):
        second += data[i]
    third = ""
    for i in range(size*2, size*3):
        third += data[i]
    if first == second and second == third:
        return True
    else:
        return False


print(data_correction('100111001011001110010110011100101'))
print(data_correction('011101111101110111110111001111'))

```

## Proof of work

<img width="1031" alt="Screenshot 2024-09-10 at 13 55 23" src="https://github.com/user-attachments/assets/77bdce7a-493e-47d6-8acf-d32c87132072">
