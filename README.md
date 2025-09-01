# Hashira Placements - Polynomial Coefficients Calculator

## Problem Summary
Given `n` roots of a polynomial expressed as strings in various bases, this program converts the roots to decimal and computes the coefficients of the polynomial whose roots are those given numbers. The polynomial is of degree `m = k-1` where `k` is the minimum number of roots required. The output is the expanded polynomial coefficients from highest degree to constant term.

---

## Input Format
- The roots are provided as pairs `(base, value)` where `value` is a string representing the root in the specified `base`.
- `n` = total number of roots.
- `k` = minimum number of roots required to uniquely determine the polynomial coefficients (`k = m + 1` where `m` is polynomial degree).
- The program currently uses hardcoded example roots; to adapt, replace the roots vector in the source code.

---

## Sample Test Case 1 (Small)

Input:
```cpp
int n = 4, k = 3;
vector<pair<int,string>> roots = {
    {10, "4"}, {2, "111"}, {10, "12"}
};

