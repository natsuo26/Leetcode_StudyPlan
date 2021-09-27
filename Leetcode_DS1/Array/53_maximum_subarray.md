## #53 Maximum Subarray

### Approach 1
1. Create 2 variables, lets name them current_sum and max_sum and store vector's value at 0th index.
2. Iterate over the vector and use max function to comare which is larger,<i><b> current_sum</i> or <i>current_sum+<vector_name>[i]</b></i>
and store that larger value in current_sum.
3. Now comapare which is larger between <i><b>current_sum and max_sum</b></i> and store it in max_sum variable. 
4. When the loop is over we will get the maximum possible value of a subarray, return max_sum.