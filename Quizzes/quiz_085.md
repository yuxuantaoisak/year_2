## Paper work


## Code


```.py

def merge_sort(m):
    if len(m) == 1:
        return m
    mid = len(m) // 2
    left = merge_sort(m[:mid])
    right = merge_sort(m[mid:])
    s, i, j = [], 0, 0
    while i < len(left) and j < len(right):
        if left[i] < right[j]:
            s.append(left[i])
            i += 1
        else:
            s.append(right[j])
            j += 1
    return s + left[i:] + right[j:]


print(merge_sort([10, 5, 1, 9]))


```


## Proof of work

<img width="995" alt="Screenshot 2024-09-27 at 14 53 02" src="https://github.com/user-attachments/assets/8f7d1a17-66ba-4af2-9412-2a92ed121d66">
