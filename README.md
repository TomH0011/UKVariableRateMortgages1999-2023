To be ablke to run this you must download the data from kaggle

https://www.kaggle.com/datasets/liamhealy/uk-mortgage-rates

Save it to files
Unzip it
Copy the file path to the correect line in the CallingData module

Run main


The goal of this code was to predict Variable interest rate for UK housing mortgages using historic data on variable interest rates, 
the yields of ten year long government bonds and the bank of englands interest rates.
With a datetime index I calculate the rolling averages and yearly and monthly averages to make better predictors of the variable interest rates
and at the end I show I got it close!
I also point out outliers and where they may have arisen by doing analysis on the differences between my prediction and and the actual interest rate
