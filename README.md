# insert

```
def insert_sort2(target_list):
    assert isinstance(target_list, list)
    if not target_list:
        return target_list
    for i in range(1, len(target_list)):
        key = target_list[i]
        j = i - 1
        while j >= 0 and key > target_list[j]:
            target_list[j + 1] = target_list[j]
            j -= 1

        target_list[j + 1] = key

    return target_list

```
