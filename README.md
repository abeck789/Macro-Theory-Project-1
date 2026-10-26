# Macro-Theory-Project-1

Part 1:

For the purposes of this project, Colombia is an emerging country, and Ireland is the developing country of choice. Philippines is our low-income country. 

GDP per capita (current US$) for Ireland, Colombia, and the Philippines were obtained from the World Bank Development Indicators database. The database was cleaned by extracting all nonessential columns and preparing a panel dataset. There were no missing observations.

Data from all three countries were initially organized into separate sheets within the same Excel file for data cleaning purposes. Data were organized in a panel (long-format) dataset consisting of country, year, GDP per capita, total factor productivity, population growth, inflation, and gross capital formation observations for Ireland, Colombia, and the Philippines. The datasets were merged into a single master file and reviewed for consistency across variables and years.

Inflation rate, consumer prices for Colombia, Ireland, and the Philippines (percent, annual, not seasonally adjusted) were downloaded from the Federal Reserve Bank of St. Louis (https://fred.stlouisfed.org). 

Total factor productivity at constant national prices, annual, not seasonally adjusted, for Colombia, Ireland, and the Phillipines was obtained from the Federal Reserve Bank of St. Louis (https://fred.stlouisfed.org). The database was cleaned by extracting all nonessential columns and preparing a panel dataset. There were no missing observations.

Data availability differed across variables. Total factor productivity data was available through 2023, while other variables extended to 2025. To maintain a balanced dataset and ensure consistency across observations, the sample period was restricted to 1960-2023.

Population, persons, annual, not seasonally adjusted data was available from 1960 to 2025 via the Federal Reserve Economic Data, Federal Reserve Bank of St. Louis. To maintain a balanced data set, data for population was restricted to 1960-2023. 

Gross capital formation (% of GDP) data was obtained from the World Bank Group (data360.worldbank.org). Data was obtained from the time frame of 1960-2025, but was restricted to 2023 for the sake of continuity. Philippines only had data from 1981 to 2025, and Ireland only had data from 1970 to 2025. 

Gross capital formation contained missing observations during the early years of the sample period. Because interpolation is not appropriate when missing values occur at the beginning of a series and no preceding observations exist, these observations were omitted from the final regression analysis. 

GDP per capita (current US$) was selected as the dependent variable because it is a widely used measure of economic performance and living standards. The independent variables were chosen based on their theoretical relationship with economic growth and data availability for Ireland, Colombia, and the Philippines over the study period.

Total factor productivity (TFP) was included to measure the efficiency with which labor and capital are transformed into output. Improvements in productivity allow economies to produce more goods and services with existing resources and are widely recognized as a key driver of long-run economic growth.

Population growth was included because changes in population affect labor force size, resource allocation, and capital available per worker. Growth theories suggest that population dynamics can influence both economic output and GDP per capita.
Inflation was incorporated as a measure of macroeconomic stability. High or persistent inflation can reduce purchasing power, create economic uncertainty, discourage investment, and negatively affect long-term growth prospects.

Gross capital formation (% of GDP) was included as a measure of investment within an economy. Gross capital formation reflects expenditures on fixed assets such as infrastructure, buildings, machinery, and equipment. Higher levels of investment contribute to capital accumulation, which enhances productive capacity and supports economic growth.

Part 2:
Ireland experienced the fastest growth. Ireland’s GDP growth has been supported heavily by exports, especially with goods such as pharmaceuticals. Ireland has low corporate tax rates. Ireland is the second richest economy in the world according o the International Trade Administration. Philippines had the most volatile growth, which could be linked to its increasing young workforce. The World Bank indicated that 90% of growth since 2010 in the country came from capital accumulation. Volatility could also be attributed to political instability, inflation, and/or other factors. 

Results indicate that TFP, Inflation, and GCF are statistically significant predictors of GDP per capita, while Pop_Growth is not significant at the 0.05 level. Inflation is negatively associated with GDP per capita, while TFP and GCF are positively associated.The model explains approximately 80.92% of the variance in GDP per capita (R-squared = 0.8092). Missing values were handled by filtering the dataset to include only complete cases for the variables of interest, which may have reduced the sample size and potentially affected the generalizability of the results.

Part 3:

Ireland was on the move pre-1990. The early effects of the Industrial Revolution in Britain spilled over into Ireland (Bradley 1999). The Act of Union united Great Britain and Ireland under the name of the United Kingdom and there were considerable economic benefits that conferred because of this independence. However, the Act of the Union was immediately followed by a long period of economic decline. The rise of the adoption of free trade and capitalism prompted economic growth. Large scale financial support in the north of Ireland sustained the north during this period. 

Between 1990 and 2007, Ireland endured the “Celtic Tiger” period(1994-2008). Employment almost doubled. Immigration increased, and the population became more diverse. The Celtic Tiger felt a sharp dip in September 2008. This period of Great Normalisation can be attributed to the political decisions that were made during this time. Some individuals believed Ireland was a tax haven for corporations to pay little tax (O’Malley 2020). 

From 2008 onward, the 2008 recession impacted Ireland as well as the rest of the globe. An increase in technological advancement and investment in corporations like pharmaceuticals have positively increased GDP per capita. 

Part 4: 
Investment is the most critical variable overall. It has the positive, statistically significant coefficient (0.285). Investment is positively associated with GDP per capita growth, while population growth is negatively associated (still statistically significant). Human capital is negative but statistically significant at the 0.05 level. Higher levels of human capital are associated with lower levels of GDP per capita. The model explains approximately 16.21% of the variance in GDP per capita growth (R-squared = 0.1621). 

Missing data can definitely influence the results because missing data can effect coefficients, significance levels, and thus r-squared. Countries with thorough data may be overrepresented. There are also proxies. GDP per capita growth does not account for welfare of citizens, and population growth does not account for labor-force participation. 
