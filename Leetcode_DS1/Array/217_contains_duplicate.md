## #217 Contains Duplicate

### Approach 1
1. Sort the vector.
2. Traverse through the vector and find if two consecutive elements are same.
3. If yes, return True. Else, return false.

### Approach 2
1. Store size of the vector in a variable n.
2. Make an unordered_map<int,int>m.
3. Start to store the keys and values into the map from index 0 to n-1 from given vector in a for loop using m[nums[i]]++.
4. Now we iterate over the map and look for the value which is grater than or equal to 2, if the condition is met we return true else when loop ends we return false.