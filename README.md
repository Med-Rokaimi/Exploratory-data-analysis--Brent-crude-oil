Notebooks:
1. Crude_Oil_Price_Analysis.ipynb
  This notebook is for analyzing and exploring the Brent close prices.

3. crude_oil_data_collection_and_processing.ipynb
   This notebook for collecting and processing external features added to the Brent prices. In this notebook,
   - I collected many timeseries form different sources;
   - Merged all the time series into one dataframe based on the Brent Dates index (left join);
   - Filled missing values using a linear method;
   - Scaled and normalized the data;
   - Conducted time series decomposition;
   - Performed the Spearman correlation test.

Data sets:
1. oil.xlsx: a clean dataset spans the period from 2012 to 2021 and includes the following columns: Date, Brent close price (Price), USDX price index (USD), Saudi energy sector index (Energy), and sentiment analysis scores (Sentimen). The data for the Brent close price, USDX price index, and Saudi energy sector index were collected from Investing.com.  https://www.investing.com
The sentiment analysis scores were obtained from the Crude Oil Sentiment 2022 Dataset.
https://github.com/fhgr/crudeoil-sentiment2022-dataset.

2. Features.xlsx: a crude dataset includes several .stocks and indexes including USD, GOLD, Brent, GAS and sentimental score. 



