Debugging
1. The bug was that the calculateSum function was performing string concatenation instead of addition, because it was being passed strings instead of numbers.
2. To fix the problem, we can convert the operands of the + operator to numbers using the Number() Javascript function. Then, the + operator will perform addition, as desired.
