# 209poll

## Purpose


compute the confidence intervals, knowing that:
* the 95% confidence interval amplitude is 2 × 1.96√v
* the 99% confidence interval amplitude is 2 × 2.58√v

where v stands for the variance of the sample proportion (corrected for finite populations).

The goal of this project is to compute the 95% and 99% confidence intervals.


## Usage
``` bash
./209poll pSize sSize p
```

## DESCRIPTION
``` bash
pSize size of the population
sSize size of the sample (supposed to be representative)
p percentage of voting intentions for a specific candidate
```

## Result

|test-type| passed |
|--|--|
|1 - rigor | 100 % |
|2 - minimum tests | 100 % |
|3 - regular test | 100 % |
|4 - tricky tests | 100 % |

|Total| 100 % |
|--|--|



## License
[Loïs Bentrari](https://www.linkedin.com/in/lo%C3%AFs-bentrari/)
