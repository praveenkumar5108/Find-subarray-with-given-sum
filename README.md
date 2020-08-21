# Find-subarray-with-given-sum
A simple solution is to consider all subarrays one by one and check the sum of every subarray. Following program implements the simple solution. Run two loops: the outer loop picks a starting point I and the inner loop tries all subarrays starting from i.
# Algorithm

1.Traverse the array from start to end.
2.From every index start another loop from i to the end of array to get all subarray starting from i, keep a varibale sum to calculate the sum.
3.For every index in inner loop update sum = sum + array[j]
4.If the sum is equal to the given sum then print the subarray.
