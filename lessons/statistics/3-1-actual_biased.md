[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

```{python}
actual_pmf = thinkstats2.Pmf(resp['numkdhh'], label='actual')
biased_pmf = BiasPmf(pmf, label='observed')

thinkplot.PrePlot(2)
thinkplot.Pmfs([actual_pmf, biased_pmf])
thinkplot.Config(xlabel='Children older than 18', ylabel='PMF')

print('Unbiased mean', actual_pmf.Mean())
print('Biased mean', biased_pmf.Mean())
```
Result:
Unbiased mean 1.024205155043831
Biased mean 2.403679100664282
