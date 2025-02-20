# Sliding Window Algorithm

### Identification:
- We will be given a Array or Substring in problem statement.
- Question will be talking about subarray or substring.
- Additionally a value k(window size) or a condition will be given.
- And we will be asked to find some min/max value for window size k or to minimize/maximize window size.

### Origin of Sliding Window:
- Without sliding window concept - brute force solution of above type of problem will genrally use nested loops therefor time complexity will be O(n^2)
- In brute force solution we will be doing a lot to repeated work - by evaluating complete window again.
- Instead if we just remove first index value from our window and include array next index value in window(sliding mechanism) - we will get one output for evaluation. This will avoid nested loops and time complexity will improve(generally O(n)).
> When optimizing our program, first write brute force solution and then check if there if any repeated work being done. If yes, how can it be avoided - this way we can optimize our code.

### Variations of Sliding Window problems:
- Fixed size sliding window
- Variable size sliding window

### Important Problems
