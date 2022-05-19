# (Banking And Systemic Crises)
## prepared by (Mohamed Abd Al-mgyd)
>>> https://github.com/1145267383

>>> https://github.com/1145267383/Systemic-And-Banking-Crises

### Web APP
>>> https://crises.herokuapp.com/ 

## Dataset

> A)20160923_global_crisis_data:
This data was collected over many years by Carmen Reinhart (with her coauthors Ken Rogoff, Christoph Trebesch, and Vincent Reinhart). 
"https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx".

>> This data contains the banking crises of 70 countries, from 1800 AD to 2016 AD, with a total of 15,190 records and 16 variables.
But the data stabilized after cleaning and adjusting to 8642 records and 17 variables.

> B)Label_Country:
This data contains a description of the country whether it's Developing or Developed .


> Variable:   Description:

> 1-Case: ID Number for Country.

> 2-Cc3: ID String for Country.

> 3-Country : Name Country.

> 4-Year: The date  from 1800 to 2016.

> 5-Banking_Crisis: Banking problems can often be traced to a decrease the value of banks' assets.    
                                                             
          >> A) due to a collapse in real estate prices or When the bank asset  values decrease substantially .
          >> B) if a government stops paying its obligations, this can trigger a sharp decline in value of bonds.

> 6-Systemic_Crisis : when many banks in a country are in serious solvency or liquidity problems at the same time—either:

        >> A) because there are all hits by the same outside shock.
        >> B) or because failure in one bank or a group of banks spreads to other banks in the system.

> 7-Gold_Standard: The Country have crisis in Gold Standard.

> 8-Exch_Usd: Exch local currency in USD, Except exch USD currency in GBP.

> 9-Domestic_Debt_In_Default: The Country have domestic debt in default.

> 10-Sovereign_External_Debt_1: Default and Restructurings, -Does not include defaults on WWI debt to United States and United Kingdom and post-1975 defaults on Official External Creditors.

> 11-Sovereign_External_Debt_2: Default and Restructurings, -Does not include defaults on WWI debt to United States and United Kingdom but includes post-1975 defaults on Official External Creditors.

> 12-Gdp_Weighted_Default:GDP Weighted Default for country.

> 13-Inflation: Annual percentages of average consumer prices.

> 14-Independence: Independence for country.

> 15-Currency_Crises: The Country have crisis in Currency.

> 16-Inflation_Crises: The Country have crisis in Inflation.

> 17-Level_Country: The description of the country  whether it's Developing or Developed. 


# Summary of Findings
## The effect of variables on systemic and banking crisis
#### (1)
>- the occurrence of `Banking Crisis` Cause in a `Systemic Crisis`, at a rate of `62%`.
>- In contrast, that the occurrence of `Systemic Crisis` It was because a `Banking Crisis`, at a rate of `91%`.
>- The occurrence rate  of `Banking Crisis` are higher than `Systemic Crisis` by `47%`.

#### (2)
>-  That a {Gold Standard, Exch USD, GDP Weighted Default } `has no clear affect` on  banking crisis and systemic crisis.
>- That each from {Domestic Debt In Default, Sovereign External Debt 1, Sovereign External Debt 2,  Independence,  Currency Crises, Inflation Crises, Inflation} `has affect` on banking crisis and systemic crisis by `positive`.
>- And that `Level Country` has affect on ` banking crisis` by negative, but  not clear with `systemic crisis`.

#### (3)
>There a relationship between each from `Inflation` and `Inflation crises` and `Currency Crises`,And also between each from `Domestic Debt In Default` and `Sovereign External Debt 1` and  `Sovereign External Debt 2` and `GDP Weighted Default`.

## Test the correlation of some variables with some.
>- Systemic_Crisis And Gold_Standard >>>Independent > **Relationship=60%**.
>- Banking_Crisis And Gold_Standard >>>Independent > **Relationship=16%**.
>- Systemic_Crisis And Level_Country >>>Independent > **Relationship=12%**.
>- Banking_Crisis And Level_Country >>>Dependent > **Relationship=97%**.

##  Study the effect of developed countries (USA) on developing (Egypt).
#### (1)
>-  The occurrence of a {Systemic Crisis,Banking Crisis,Gold Standard,Currency Crises} in `US` leads to its `occurrence` in `Egypt`.
>-There a interconnection between the occurrence of `Inflation` in `US`  and  its occurrence in `Egypt`.

#### (2)
>- The occurrence of a Crisis in {Domestic Debt In Default,Sovereign External Debt 1,Sovereign External Debt 2,Inflation Crises,a different in GDP Weighted Default } in `US` does `not leads` to its occurrence in `Egypt`.

#### (3)
>- Exch {`USD` by `GBP`} affect in Exch {`EGP` by `USD`}.
>>- That is, the `high` the value of the `USD`, the `low` the value of the `EGP`.
