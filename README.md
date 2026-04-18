🧮 Algorithm – Array Manipulation (Prefix Sum Method)
Start
Read input values n (array size) and queries.
Create an array arr of size n + 1 initialized with zeros.
For each query (a, b, k):
Add k to arr[a − 1]
Subtract k from arr[b]
Initialize two variables:
current = 0
max_val = 0
Traverse the array from index 0 to n − 1:
Add each element to current
Update max_val if current > max_val
Return max_val
End ✅
📊 Complexity
Time Complexity: O(n + m)
Space Complexity: O(n)

This algorithm efficiently finds the maximum value after range updates without modifying each element individually.
