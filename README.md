# Advanced Feature Engineering of Raw Data of Stocks with PySpark

* The notebook contains processing of quotes of several stocks that I downloaded from the site http://firstratedata.com.
* I built features and labels in a recursive matter using historical data. The features and labels engineering is performed by pyspark on an AWS cluster, so the processing is completely parallel, and can process huge data volumes.
* Labels were produced for each stock and for each day, denoting whether the closing price of the next day will be lower or higher than the current day's.
* The goal of the project was to examine whether said labels can be predicted using features based on historical stock quote data, or whether they are too random.
* The result was that the labels indeed seem too random to predict using the features I built.

For a better view of the notebook: https://nbviewer.jupyter.org/github/MiaDor12/Advanced_Feature_Engineering_of_Raw_Data_of_Stocks-with_PySpark/blob/master/Advanced%20feature%20engineering%20with%20pyspark%20on%20raw%20data%20of%20stocks.ipynb
