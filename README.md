# cis-320-BLA
The potential outliners for my data
  boxplot.stats(cis$popestimate2014)$out
by changing the coef argument to 3 to identify suspected my data outliers.
  boxplot.stats(cis$popestimate2014, coef = 3)$out
I am going to do the same thing with my data with popestimate 2015
The last step of my report is to do the graph for state of region and state of division
        barplot(table(cis$STATE,cis$REGION), legend.text=TRUE)
        plot(cis$STATE, cis$REGION)
