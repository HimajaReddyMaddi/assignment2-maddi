### Himaja Reddy Maddi

Currently I am staying Maryville since past 4 weeks ago. I am pursuring Master's at Norwest Missouri State University. I enjoy spending some quality time with family.

![MyPicture](C:\Users\S545156\Documents\GitHub\assignment2-maddi\picture.jpg)

***
### Recommendations for food

In the table below I would like to provide the information about food items and the location of availability and the cost of food item.

|Food/Drink|Location|Price|
|----|----|----|
|Chicken Biryani|Paradise Hyd|300|
|Fish Biryani|Tabla Hyd|350|
|Ice Cream| Cream Stone Hyd|150|
|Nutella Shake| MOM's Hyd| 180|

***
### Quotes Section

> "If you want to live a happy life, tie it to a goal, not to people or things."
                                                 - *Albert Einstein*

> "Many of life’s failures are people who did not realize how close they were to success when they gave up."
                                                - *Thomas A. Edison*

***

#### Algorithm for Power of Factorial Divisor
> Find maximum power of a number that divides a factorial. If multiple powers of a prime factor are present in n, then we divide the count to get the maximum power value for this factor. 
GeeksforGeeks<https://www.geeksforgeeks.org/find-maximum-power-number-divides-factorial/>

```
int fact_pow (int n, int k) {
    int res = 0;
    while (n) {
        n /= k;
        res += n;
    }
    return res;
}

```

Codelink<https://cp-algorithms.com/algebra/factorial-divisors.html>