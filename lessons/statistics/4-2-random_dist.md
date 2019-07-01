[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)
import numpy as np
rando = np.array(np.random.random(1000))
pmf = thinkstats2.Pmf(rando)
thinkplot.Pmf(pmf)
cdf = thinkstats2.Cdf(rando)
thinkplot.Cdf(cdf)
