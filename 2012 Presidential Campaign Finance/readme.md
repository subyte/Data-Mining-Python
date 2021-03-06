2012 Presidential Campaign Finance (2012 Presidential Campaign Finance.ipynb)
--------------------------------

Download the data set for 2012 Presidential Campaign Contributions from  ftp://ftp.fec.gov/FEC/Presidential_Map/2012/P00000001/P00000001-ALL.zip.

Unzip and rename the file as follow:
```Python
unzip P00000001-ALL.zip
mv P00000001-ALL.csv donations.txt
```

Quick look at the first 6 lines of the data set:
```Python
head -n6 donations.txt
```

1) Output the basic statistics of Obama's and Romney's campaign finance (total non-zero/non-refund donations, minimum donation, maximum donation, average donation amount, median donation amount and standard deviation). Also maps the normalized sample contributions and z-score for the donation amounts of $20000, $10000, $5000, $1000, $500, $250, $100 and $50.

2) Compare Obama's and Romney's campaign donations by states. **Output**: states.txt. 

- Obama's campaign donations by states:
![obama.png](https://github.com/shngli/Data-Mining-and-Manipulation-Python/blob/master/2012%20Presidential%20Campaign%20Finance/obama.png)

- Romney's campaign donations by states:
![romney.png](https://github.com/shngli/Data-Mining-and-Manipulation-Python/blob/master/2012%20Presidential%20Campaign%20Finance/romney.png)

3) Compare Obama's and Romney's monthly campaign donations between March 2011 and December 2012.
![obamaRomney.png](https://github.com/shngli/Data-Mining-Python/blob/master/2012%20Presidential%20Campaign%20Finance/obamaRomney.png)

4) Compare Obama's and Romney's cumulative campaign donations between March 2011 and December 2012.
![cumulative donations.png](https://github.com/shngli/Data-Mining-Python/blob/master/2012%20Presidential%20Campaign%20Finance/cumulative%20donations.png)

5) Compare Obama's and Romney's cumulative campaign reattributions between March 2011 and December 2012.
![cumulative reattributions.png](https://github.com/shngli/Data-Mining-Python/blob/master/2012%20Presidential%20Campaign%20Finance/cumulative%20reattributions.png)

6) Compare Obama's and Romney's cumulative campaign refunds between March 2011 and December 2012.
![cumulative refunds.png](https://github.com/shngli/Data-Mining-Python/blob/master/2012%20Presidential%20Campaign%20Finance/cumulative%20refunds.png)

7)  Compares frequency of Obama's and Romney's campaign donations with a histogram between -$3000 and $3000 and a boxplot. 

![obama romney histogram.png](https://github.com/shngli/Data-Mining-Python/blob/master/2012%20Presidential%20Campaign%20Finance/obama%20romney%20histogram.png)

![obama romney boxplot.png](https://github.com/shngli/Data-Mining-Python/blob/master/2012%20Presidential%20Campaign%20Finance/obama%20romney%20boxplot.png)

8) Perform ttests on Obama's and Romney's campaign donations data
