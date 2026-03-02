def merge_sorted(list1, list2):
    i, j = 0, 0
    result = []
    while i < len(list1) and j < len(list2):
        if list1[i] <= list2[j]:
            result.append(list1[i])
            i += 1
        else:
            result.append(list2[j])
            j += 1
    if i < len(list1):
        result.extend(list1[i:])
    if j < len(list2):
        result.extend(list2[j:])
    return result
