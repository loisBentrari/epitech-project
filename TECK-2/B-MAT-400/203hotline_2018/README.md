# 203hotline

## Purpose

Deduce from the past results the probability to sell a $x jacket and $y trousers together.

Reckons 3500 people could possibly call during each 8-hour day, and would like to know the probability of an overload (that is, the probability of no line being available), depending on the average duration of calls.

* First task is to compute the binomial coefficient *(n/k)* given *k* and *n* (emphasizing the computation speed and stack optimization).

* Second task is to compare the binomial and Poisson distributions, given the average duration of calls, by printing:
   - the probabilities of getting n simultaneous calls (for n increasing from 0 to 50),
   - the probability of an overload,
   - the computation time.



## Usage
``` bash
./203hotline [n k | d]
```

## DESCRIPTION
``` bash
n n value for the computation of C(n, k)
k k value for the computation of C(n, k)
d average duration of calls (in seconds
```

## Result

|test-type| passed |
|--|--|
|1 - rigor | 100 % |
|2 - minimum-tests | 83,3 % |
|3 - combination | 66,7 % |
|4 - binomial | 100 % |
|5 - Poisson | 100 % |
|6 - overload | 100 % |
|7 - mathematical rigor | 66,7 % |

|Total| 89,2 % |
|--|--|



## License
[Loïs Bentrari](https://www.linkedin.com/in/lo%C3%AFs-bentrari/)
