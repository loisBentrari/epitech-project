# 201yams

## Purpose

Developing a software that will give you the chances to obtain a given combination on the next
dice roll.

## Usage
``` bash
./201yams d1 d2 d3 d4 d5 c
```

## DESCRIPTION
``` bash
d1 value of the first die (0 if not thrown)
d2 value of the second die (0 if not thrown)
d3 value of the third die (0 if not thrown)
d4 value of the fourth die (0 if not thrown)
d5 value of the fifth die (0 if not thrown)
c expected combination
```

## Combination

* a pair (at least 2 dice of the same value),
* a three-of-a-kind (at least 3 dice of the same value),
* a four-of-a-kind (at least 4 dice of the same value),
* a full house (one pair and one three-of-a-kind),
* a straight (5 dice of sequential value),
* a yahtzee (5 dice of the same value).

## Result

|test-type| passed |
|--|--|
|1 - rigor | 85,7 % |
|2 - minimum-tests | 85,7 % |
|3 - pair | 100 % |
|4 - three-of-kind | 100 % |
|5 - four-of-kind | 100 % |
|6 - full-house | 30 % |
|7 - straight | 10 % |
|8 - yams | 100 % |

|Total| 61,4 % |
|--|--|



## License
[Loïs Bentrari](https://www.linkedin.com/in/lo%C3%AFs-bentrari/)
