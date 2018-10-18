# insert

```diff python
def insert_sort2(target_list):
+    "插入排序（倒序）"
-    assert isinstance(target_list, list)
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
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item




#1
mojombo#1
mojombo/github-flavored-markdown#1



~~this~~
