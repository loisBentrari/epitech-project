# 207demography

## Purpose

A file named **207demography_data.csv**, which gives an estimation of every country’s population from 1960 onwards.

If world population growth seems exponential in the longterm, in a shorter term it seems linear: using this data, you must establish the linear least squares regression
that will allow you to predict population depending on the year.
In the following, Y is the population (in million people) and X the year. With one or several country codes
as inputs, your program will print:
1. the aX and bX coefficients of the linear fit Y = aXX + bX,
2. the root-mean-square deviation of this fit,
3. the population prediction in 2050 according to this fit,
4. the aY and bY coefficients of the linear fit X = aY Y + bY ,
5. the root-mean-square deviation of this fit,
6. the population prediction in 2050, according to this fit,
7. the correlation coefficient between X and Y .


## Usage
``` bash
./207demography code [...]
```

## DESCRIPTION
``` bash
code country code
```

## Result

|test-type| passed |
|--|--|
|1 - rigor | 100 % |
|2 - minimum tests | 100 % |
|3 - standard deviation | 100 % |
|4 - fit | 100 % |
|5 - extrapolation | 100 % |
|6 - correlation | 100 % |

|Total| 100 % |
|--|--|



## License
[Loïs Bentrari](https://www.linkedin.com/in/lo%C3%AFs-bentrari/)
