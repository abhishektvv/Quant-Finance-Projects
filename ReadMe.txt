After storing all the files in the same folder, execute 
Volatility Smile III-Option Expiry 14 Aug 2025 - Implied Volatility Computation and Benchmark.ipynb

We require Option Expiry 14-Aug-2025.csv to run this file. The python file Volatility Smile III-Option Expiry 14 Aug 2025 - Implied Volatility Computation and Benchmark.ipynb is for computing implied volatilities using Newton Raphson, Brentq and saving all the data in a file. In the process we also compute performance metrics. The performance metrics may vary based on external factors. 

The subsequent python files use a csv file that was created after computing IV in the above python program. Hence it won't run properly unless the first file is executed.

In Volatility Smile IV-Option Expiry 14 Aug 2025 Plotting Vol Smile and Surface.ipynb, we chose 10 timestamps in random for plotting the volatility smile. So we may not get the same set of smiles as mentioned in the report. 

In Volatility Smile V - Newton Raphson Bar Charts.ipynb, we just do Nan classification and look at the frequency of iteration times using Newton Raphson. 
