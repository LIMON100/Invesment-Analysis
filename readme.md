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
