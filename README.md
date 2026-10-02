# first
# Arithmetic Program Report

## Data Contract

### Input
The program accepts two integers `a` and `b`, separated by a space.

### Output
The program produces two results:
1. The sum of `a` and `b`.
2. The value of `a` raised to the power of `b`.

## Arithmetic Extension

I added exponentiation as a new arithmetic operation.

```python
d = a ** b
```
## Tests

### Test 1
Input: `2 -3`
Output: `-1`, `0.125`
Result: PASS

### Test 2
Input: `5 4`
Output: `9`, `625`
Result: PASS

### Test 3
Input: `1 2`
Output: `3`, `1`
Result: PASS

### Test 4
Input: `-3 2`
Output: `-1`, `9`
Result: PASS

## Extension Test

The extension tested was exponentiation (`a ** b`).

Input: `2 5`  
Expected exponentiation result: `32`  
Actual exponentiation result: `32`  
Result: PASS

## AI-Use Note

### Help Received
I used ChatGPT to help me understand the assignment, the data contract, and how to record the test results.

### Changes Made
I added exponentiation as a new arithmetic operation and documented the test results in the README.

### Checks Performed
I ran the program with different inputs and checked that the actual outputs matched the expected results.