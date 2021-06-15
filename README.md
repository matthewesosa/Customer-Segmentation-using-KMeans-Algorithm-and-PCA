# Customer-Segmentation-using-KMeans-and-PCA
Customer Segmentation using KMeans and PCA

SEGMENTATION DATA:
The fast-moving consumer goods (FMCG) business data set I am using contains information of about 2000 people from a giving area patronizing the business in question. The information in the data summarizes the description of the kind of customers entering a physical FMCG store and all data has been collected through the 'loyalty card' they used. At the end of this notebook you will discover that I have been able to apply the KMeans++ algorithm and Principal Component Analysis to detect similar qualities among the different customers and separated the customers into different 'social groups' (which I have refered to here as segments or clusters)

SEGMENTATION DATA - LEGEND:
Variable - (Data type) -	Range -	Description

ID - numerical - Integer - Shows a unique identificator of a customer.	

Sex - categorical	- {0,1} -	Biological sex (gender) of a customer. In this dataset there are only 2 different options.					
0	male							
1	female

Marital status - categorical - {0,1}	Marital status of a customer.						
0	single							
1	non-single (divorced / separated / married / widowed)	

Age -	numerical -	Integer -	The age of the customer in years, calculated as current year minus the year of birth of the customer at the time of creation of the dataset
18	Min value (the lowest age observed in the dataset)						
76	Max value (the highest age observed in the dataset)		

Education -	categorical -	{0,1,2,3} -	Level of education of the customer						
0	other / unknown							
1	high school							
2	university							
3	graduate school	

Income -	numerical -	Real -	Self-reported annual income in US dollars of the customer.						
35832	Min value (the lowest income observed in the dataset)						
309364	Max value (the highest income observed in the dataset)	

Occupation -	categorical -	{0,1,2} -	Category of occupation of the customer.						
0	unemployed / unskilled						
1	skilled employee / officialE32						
2	management / self-employed / highly qualified employee / officer	

Settlement size - categorical -	{0,1,2}	- The size of the city that the customer lives in.						
0	small city							
1	mid-sized city							
2	big city
