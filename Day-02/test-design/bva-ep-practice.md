# BVA & EP Practice

## Example: Username Length

**Requirement:** Username should contain 5–15 characters.

### Boundary Value Analysis (BVA)

| Test Value | Expected Result |
| ---------: | --------------- |
|          4 | Invalid         |
|          5 | Valid           |
|          6 | Valid           |
|         14 | Valid           |
|         15 | Valid           |
|         16 | Invalid         |

### Equivalence Partitioning (EP)

| Partition | Test Value | Expected Result |
| --------- | ---------: | --------------- |
| Invalid   |          4 | Invalid         |
| Valid     |          8 | Valid           |
| Valid     |         14 | Valid           |
| Invalid   |         16 | Invalid         |

## Key Learning

BVA focuses on values around the boundaries, while EP divides input data into valid and invalid groups.
