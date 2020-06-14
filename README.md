# Retail-Analytics
Walmart sales prediction with ML


## Dataset
The dataset is taken from [Kaggle](https://www.kaggle.com/manjeetsingh/retaildataset), and consists of three csv files:
1. **features:**

Store |	Date | Temperature	| Fuel_Price| 	MarkDown1 |	MarkDown2	| MarkDown3	| MarkDown4	| MarkDown5	| CPI	| Unemployment	| IsHoliday |
-----|---------|---------|--------|--------|--------|-----|---------|---------|--------|--------|--------|
1	| 05/02/2010	| 42.31	| 2.572	| NA	| NA	| NA	| NA	| NA	| 211.0963582 | 8.106	| FALSE|
1	|12/02/2010	|38.51	|2.548|	NA	|NA|	NA|	NA|	NA	|211.2421698|	8.106|	TRUE
1	|19/02/2010|	39.93|	2.514|	NA|	NA	|NA|	NA	|NA|	211.2891429	|8.106	|FALSE
1	|26/02/2010	|46.63|	2.56|	NA	|NA|	NA	|NA	|NA	|211.3196429	|8.106	|FALSE
1	|05/03/2010	|46.5|	2.625|	NA|	NA|	NA|	NA	|NA|	211.3501429|8.106	|FALSE

2. **sales:**

Store|	Dept|	Date|	Weekly_Sales|	IsHoliday
-----|---------|---------|--------|--------
1|	1|	05/02/2010|	24924.5|	0
1|	1|	12/02/2010|	46039.49|	1
1|	1|	19/02/2010|	41595.55|	0
1|	1|	26/02/2010|	19403.54|	0
1|	1|	05/03/2010|	21827.9|	0

3. **stores:**

Store|	Type|	Size
---|---|---
1 |A  |151315
2 |A	|202307
3	|B	|37392
4	|A	|205863
5	|B	|34875
