## PerfectNumber

```
PerfectNumber(n)
```

> returns the `n`th perfect number. In number theory, a perfect number is a positive integer that is equal to the sum of its proper 
positive divisors, that is, the sum of its positive divisors excluding the number itself. Currently `0 <= n <= 45` can be computed, otherwise the function returns unevaluated.

### Examples

```
>> Table(PerfectNumber(i), {i,5})
{6,28,496,8128,33550336}
```