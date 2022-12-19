# ZigZag Indicator in python for Technical Analysis


Implementation of the Zigzag indicator with optimization for a given dataset


Please see the code for more explanations and usages. Snippet example included. Free to use. MIT License.


How to Install and Run the Project
- Import the current files and incorporate in your ongoing implementation;
- Install the python library requirements (pandas, scipy).

Basic usage:
- The function uses the pd.DataFrame as basic dataframe for the analysis;
- Pass the dataframe to the ohlc parameter (_ohlc_df);
- Define the depth of the analysis (_depth), which is the average number of candles to between the reversal trends;
- Define the deviation (_deviation) to filter undesired reversal trends, keeping the higher trends.

It returns the pivot coordinates (x-axis and y-axis) as well as the ROI of the theorical trades in this calculated period, which a effective parameter for ML optimization and even heuristic processing.

## @liraeng
### Open to colaboration on forward thinking ideias and projects (trading, forex, crypto) #datascience
