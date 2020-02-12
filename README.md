# “Investment and the WACC: Firm-Level Evidence from France”
with *Juan Carluccio* and *Jean-Stéphane Mésonnier* (Banque de France Working Paper Nr 710, 2018)

**Abstract** : We exploit a new dataset of consolidated balance sheets for some 1,850 private French corporate groups, in order to investigate the relationship between corporate investment and the cost of capital. We notably construct firm-level measures of the weighted average cost of capital (WACC) that account for industry-specific values of the cost of equity and reflect the actual capital structure of firms. We find that a high WACC drags down investment: a one SD increase in the real WACC (+2 pp) is associated on average with a reduction by 0.65 pp in the investment rate. 

---------------------------------------------------------------------------------------------------------------------------------------

The stata data file data_CMSM_COE_WACC_A38_2003_2015.dta presents sector-year level meaures for 2003-2015 of the Cost of Equity and the WACC for French private firms used in the paper "Investment and the WACC: new micro evidence for France" 

For details of the data construction please refer to the paper's main text and appendix.

The dataset contains 30 variables: 

A38: NAF Rev2 A38 sector code
YEAR: Year 
COE_NOMINAL_i where i runs from 2 to 8: Cost of Equity (calculated with i H = i in the DDM H-Model)
COE_REAL_i where i runs from 2 to 8: COE_NOMINAL_i deflated
WACC_NOMINAL_i where i runs from 2 to 8: Weighted-average cost of capital 
WACC_REAL_i where i runs from 2 to 8: WACC_NOMINAL_i deflated

Note that our preferred estimate of the CoE and the WACC (used in the paper) is H = 5
Sector-level variables are constructed as simple averages from firm-level data described in the paper. 


