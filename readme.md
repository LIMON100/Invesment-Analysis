# Investment Analysis


## Problem Description:

Suppose i/you work for a company name 'AAA', an asset management company. 'AAA' wants to make 
investments in a few companies. The CEO of 'AAA' wants to understand the global 
trends in investments so that he can take the investment decisions effectively. 




## Constraints

'AAA' has 2 minor constraints for investments: 

1. It wants to invest between 5 to 15 million USD per round of investment 
2. It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in 


## Dataset :

We have taken real investment data from crunchbase.com
Also the dataset is provided here.




## Business Objective:

### 1. Business objective: 

The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is 
to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'. 

### 2. Goals of data analysis:

my goals are divided into three sub-goals: 
	○ Investment type analysis:
	 Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that 'AAA'  can 
	choose the type that is best suited for their strategy. 
	○ Country analysis: 
	Identifying the countries which have been the most heavily invested in the past. These will be 'AAA'  favourites as well. 
	○ Sector analysis: 
	Understanding the distribution of investments across the eight main sectors. 


### 3. Sector Classification: 

mapping.csv: This file maps the numerous category names in the companies table (such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The 
purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them. 





## Data Cleaning

How many unique companies are present in rounds2? 

How many unique companies are present in companies?        

In the companies data frame, which column can be used as the unique key for each company? 

Are there any companies in the rounds2 ﬁle which are not present in companies?

Merge the two data frames so that all variables (columns) in the companies frame are added to the rounds2 data frame. Name the merged frame master_frame. How many observations are present in master_frame?




## Funding Type Analysis:

This is the first of the three goals of data analysis – investment type analysis. 
The funding types such as seed, venture, angel, etc. depend on the type of the company (startup, corporate, etc.), its stage (early stage startup, funded startup, 
etc.), the amount of funding (a few million USD to a billion USD), and so on. For example, seed, angel and venture are three common stages of startup funding. 

-> Seed/angel funding refer to early stage startups whereas venture funding occurs after seed or angel stage/s and involves a relatively higher amount of investment. 

-> Private equity type investments are associated with much larger companies and involve much higher investments than venture type. Startups which have grown in scale may also receive private equity funding. This means that if a company has reached the venture stage, it would have already passed through the angel or seed stages. 




## Country Analysis:

Identify the top three English-speaking countries in the data frame top 10. 



## Sector Analysis:

When we say sector analysis, we refer to one of the eight main sectors listed in the mapping file (note that ‘Other’ is one of the eight main sectors; also, there are eight 
sectors if you consider the category 'Blanks' as a missing value). This is to simplify 
the analysis by grouping the numerous category lists (named ‘category_list’) in the mapping file. For example, in the mapping file, category_lists such as ‘3D’, ‘3D 
Printing’, ‘3D Technology’, etc. are mapped to the main sector ‘Manufacturing’.
 
