[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

```python
def height_cm(feet,inches):
    '''
    Converts feet/inches to cm
    '''
    return ((12*feet+inches)*2.54)

import scipy.stats
#units in cm
sig = 7.7
mu = 178
distn = scipy.stats.norm(loc=mu, scale=sig)

height_cm_1 = h(5,10)
height_cm_2 = h(6,1)

print(100*(dist.cdf(height_cm_2) - dist.cdf(height_cm_1)),'% of men within height range',sep='')
```
