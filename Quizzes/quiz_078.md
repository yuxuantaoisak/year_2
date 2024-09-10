## Paper work

![196](https://github.com/user-attachments/assets/f4a8d3af-a8bb-438b-b579-ad1de46e2e00)

## Code

```.py

def get_message(msg: str, k: int, n: int):

    positions = []
    for a in range(0, k):
        positions.append(2 ** a - 1)
    i = 0
    out = []
    for x in range(k+n):
        out.append(-1)
        if x not in positions:
            out[x] = int(msg[i])
            i += 1

    return out


print(get_message("1011", 3, 4))

```

## Proof of work

![Screenshot 2024-09-10 at 19 33 41](https://github.com/user-attachments/assets/e8ac6bc4-53fd-4b3f-82c4-ffcbd107af21)
