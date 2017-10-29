#Kadane's Algorithm


def max_sub_array(input_arr):
    max_now = input_arr[0]
    max_so_far = input_arr[0]

    for i in input_arr:
        max_now = max(i, max_now+i)
        if max_now > max_so_far:
            max_so_far = max_now
    return max_so_far

print max_sub_array([-2,3,2,-1])
