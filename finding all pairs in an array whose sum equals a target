

def find_pairs(arr, target):
    pairs = []
    seen = set()
    for num in arr:
        diff = target - num
        if diff in seen:
            pairs.append((diff, num))
        seen.add(num)
    return pairs

# Example usage
arr = [2, 4, 3, 7, 1, 5]
target = 6
print(find_pairs(arr, target))

O/p :
[(4, 2), (3, 3), (1, 5)]
