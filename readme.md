# (Banking And Systemic Crises)
## prepared by (Mohamed Abd Al-mgyd)
>>> https://github.com/1145267383

>>> https://github.com/1145267383/Systemic-And-Banking-Crises

### Web APP
>>> https://crises.herokuapp.com/ 

### Description of the research problem and information about it
("https://www.worldbank.org/en/publication/gfdr/gfdr-2016/background/banking-crisis")
("https://www.elibrary.imf.org/view/journals/001/2018/206/article-A001-en.xml)

Banking Crisis:.

*Banks are susceptible to a range of risks These include :
A) credit risk (loans and others assets turn bad and ceasing to perform).
B) liquidity risk (withdrawals exceed the available funds).
C) and interest rate risk (rising interest rates reduce the value of bonds held by the bank, and force the bank to pay relatively more on its deposits than it receives on its loans).

*Banking problems can often be traced to a decrease the value of banks’ assets. An deterioration in asset values can occur, for example:
A) due to a collapse in real estate prices or from an increased number of bankruptcies in the nonfinancial sector.
B) Or, if a government stops paying its obligations, this can trigger a sharp decline in value of bonds held by banks in their portfolios.
C) When asset values decrease substantially, a bank can end up with liabilities that are bigger than its assets (meaning that the bank has negative capital, or is “insolvent”). 
D) Or, the bank can still have some capital, but less than a minimum required by regulations (this is sometimes called “technical insolvency”).

*Bank problems can also be triggered or deepened if a bank faces too many liabilities coming due and does not have enough cash (or other assets that can be easily turned into cash) to satisfy those liabilities. This can happen, for example:
A) if many depositors want to withdraw deposits at the same time (depositor run on the bank).
B) It can also happen also if the bank’s borrowers want their money bank and the bank does not have enough cash on hand. The bank can become illiquid. 

*It is important to note that illiquidity and insolvency are two different things. For example:
A) a bank can be solvent but illiquid (that is, it can have enough capital but not enough liquidity on its hands). 
B) However, many times, insolvency and illiquidity come hand in hand. When there is a major decline in asset values, depositors and other banks borrowers often start feeling uneasy and demand their money bank, deepening the bank’s troubles.

*A (systemic) banking crisis occurs:
> when many banks in a country are in serious solvency or liquidity problems at the same time—either 
A) because there are all hit by the same outside shock. 
B) or because failure in one bank or a group of banks spreads to other banks in the system.  

*More specifically, a systemic banking crisis 
> is a situation when a country’s corporate and financial sectors experience a large number of defaults and financial institutions and corporations face great difficulties repaying contracts on time. 
As a result, non-performing loans increase sharply and all or most of the aggregate banking system capital is exhausted. 

*This situation may be accompanied by :
A) depressed asset prices (such as equity and real estate prices) on the heels of run-ups before the crisis.
B) or sharp increases in real interest rates, and a slowdown or reversal in capital flows. 
D) In some cases, the crisis is triggered by depositor runs on banks, though in most cases it is a general realization that systemically important financial institutions are in distress.

*Systemic banking crises can be very damaging: 
> They tend to lead affected economies into deep recessions and sharp current account reversals. Some crises turned out to be contagious, rapidly spreading to other countries with no apparent vulnerabilities. 

*Among the many causes of banking crises:
A) it have been unsustainable macroeconomic policies (including large current account deficits and unsustainable public debt).
B) And excessive credit booms and large capital inflows.
C) And balance sheet fragilities and combined with policy paralysis due to a variety of political and economic constraints. 
D) In many banking crises, currency and maturity mismatches were a salient feature, while in others off-balance sheet operations of the banking sector were prominent.

*A global database of banking crises was first compiled by Caprio and Klingebiel (1996). The latest version of the database, updated to reflect the recent global financial crisis, is available as Laeven and Valencia (2012). 
a) It identifies 147 systemic banking crises (of which 13 are borderline events) from 1970 to 2011. 
b) It also reports on 218 currency crises (defined as nominal depreciation of the currency vis-à-vis the U.S. dollar of at least 30 percent that is also at least 10 percentage points higher than the rate of depreciation in the year before) 
c) and 66 sovereign debt crises (defined by  government defaulting on its debt to private creditors) over the same period. 

*The database has detailed information about the policy responses to resolve crises in different countries. 
Analyses based on the dataset, such as "Cihák" and "Schaeck (2010)" suggest that consistently predicting banking crises is very difficult, but there are some variables (such as those capturing high leverage and rapid credit growth) that indicate increased likelihood of a crisis.

*Chapter 2 of the Global Financial Development Report uses the Laeven and Valencia (2012) version of the database of banking crises to analyze what works (and what does not) in banking supervision and regulation. The chapter and the underlying paper (Čihák, Demirgüç-Kunt, Martínez Pería, and Mohseni-Cheraghlou 2012) use the responses from the World Bank’s Banking Regulation and Supervision Survey (accompanying the Global Financial Development Report ) and performs an econometric analysis comparing countries that ended up in banking crises and those that managed to avoid them. 

*The report and the paper find that find that crisis-hit countries :
A) They had less stringent and more complex definitions of minimum capital, lower actual capital ratios, 
B) And it were less strict in the regulatory treatment of bad loans and loan losses and faced fewer restrictions on non-bank activities. 
C) And They had greater disclosure requirements but weaker incentives for the private sector to monitor banks’ risks Overall.
D) And They changes in regulation and supervision during the global financial crisis have been only gradual at best. Some changes, such as: increasing capital ratios and strengthening resolution regimes, have gone in the right direction (making regulation in crisis countries closer to that in non-crisis countries), but at the same time, private sector incentives to monitor banks’ risks have been weakened by some of the policy interventions during the crisis. The analysis shows scope for strengthening regulation and supervision as well as private sector’s incentives to monitor risk-taking.


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
>-  That a {Gold Standard, GDP Weighted Default } `has no clear affect` on  banking crisis and systemic crisis.
>- That each from {Exch USD, Domestic Debt In Default, Sovereign External Debt 1, Sovereign External Debt 2,  Independence,  Currency Crises, Inflation Crises, Inflation} `has affect` on banking crisis and systemic crisis by `positive`.
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
