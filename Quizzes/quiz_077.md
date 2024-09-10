## Paper work

![199](https://github.com/user-attachments/assets/ec9a12e6-89ee-4fea-9847-e2ce6c02c521)

## Code

```.py

def get_equation(k_n: int, p: int):
    out = []
    for i in range(1, k_n + 1):
        if (i & (1 << (p - 1))) != 0:
            out.append(i - 1)
    return out


print(get_equation(7, 1))
print(get_equation(7, 2))
print(get_equation(7, 3))

```

## Proof of work

![Screenshot 2024-09-10 at 19 47 12](https://github.com/user-attachments/assets/31d20c3c-9822-459c-a545-70bf009da616)
