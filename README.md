# SD-Variance-Calc-in-C
Statistics is the study and analyzation of data. It provides viable information about some 
data and is used all the time in research, academe, and even for students. Some of the most 
important concepts in statistics is standard deviation and variance of a data. Variance is defined 
as the average of the squared difference from the mean of the values. The formula for population 
variance and sample variance are as follows:

Population variance=
(Σ(x − mean)^2)/n

Sample variance=
(Σ(x − mean)^2)/(n-1)

Standard deviation determines how much the values differentiate from the mean. The 
population and sample standard deviation formulas are the following:

Population standard deviation=
√[(Σ(x − mean)^2)/(n)]

Sample standard deviation=
√[(Σ(x − mean)^2)/(n-1)]

When dealing with a population, n is the denominator, simply the number or values we are 
dealing with. When it’s a sample however, the denominator becomes n-1. This is because we no 
longer are working with the whole population, just a fraction of it. And the -1 is there to compensate 
for the lesser accuracy dealing with samples. We get an answer that is slightly more 
representative of the population even when only dealing with a sample.
With this, we decided to create a calculator that calculates the mean, variance, and 
standard deviation, as well as outputs a table of the values as you would see when manually 
doing this process. This problem is significant but can be a tedious process in statistics especially 
for large number of values. A nice feature about this calculator is that it presents the table that is
used when manually computing for this data that provides useful insight into the data set. For the 
program, the user will also have the option to pick between using the population or sample 
formulas. 
