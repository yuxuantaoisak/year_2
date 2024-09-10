## Paper work

![IMG_0174 2](https://github.com/user-attachments/assets/55e087c3-48b8-4fcb-b06e-3658b6d27600)


## Code

```.py

import matplotlib.pyplot as plt


def parity_bits(n):
    k = 0
    while 2**k < k+n+1:
        k += 1
    return k


x = []
y = []

for i in range(1, 1000):
    x.append(i)
    y.append(i/(i + parity_bits(i)))
    if i/(i + parity_bits(i)) == 0.9:
        print(i)

plt.plot(x, y)
plt.show()

```

## Proof of work

<img width="1266" alt="Screenshot 2024-09-10 at 14 04 47" src="https://github.com/user-attachments/assets/1275663c-4dd1-47ee-a89b-806f29928018">
