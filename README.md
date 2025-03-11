java c
AFE6014-B - Empirical Methods in Accounting and Finance 
Tutorial 7 notes 
1. Purpose 
Know how to use EViews 12 to conduct panel data analysis. 
2. Research question 
Investigate the impact of   a firm’s CEO age (“CEOAGE”)   on   a   firm’s   cash   holding   level   (“CASH”)
3. Data and variables 
Excel file: Data_Firms Cash Holding Level
Variables: cash ceoage firmsize leverage roa 
4. Descriptive statistics 
Quick----Group statistics--- descriptive statistics--- common sample   (try   individual   sample)

5. Correlation matrix 
View---Covariance Analysis

Covariance Analysis: Ordinary
Date:    XXX       Time: XXX
Sample: 2009 2012
Included observations:   107

6. Graph          (Relation between Cash and each independent variables) 
View---Graph—Graph Options—Graph type:   Specific:
Scatter   Details:
Fit lines: Regression Line
Multiple series: Multiple graphs - First vs. All –   click   OK




7. Pooled OLS 
Object---New Object --- Equation --- Name for object: OLS –   click   OK
Key in the following variables in Equation specification:
cash c ceoage firmsize leverage roa year03 year04 year05 year06 year07 year08 year09 year10 year11 year12 year13 year14 
Estimation   settings:
Method:   LS   -   Least   Squares   (NLS   and   ARMA)
Dependent Variable: CASH
Method:   Panel   Least Squares
Date: XXX       Time: XXX   Sample: 2003 2015
Periods   included:   13
Cross-sections   included:   18
Total panel (unbalanced) observations:   107

8. Residual checks代 写AFE6014-B - Empirical Methods in Accounting and Finance Tutorial 7SQL
代做程序编程语言 
View --- Actual,Fitted,Residual --- Actual,Fitted,Residual Table

View --- Actual,Fitted,Residual --- Actual,Fitted,Residual   Graph

View --- Actual,Fitted,Residual --- Residual Graph

9. Residual Diagnostics tests for OLS Normality 
View ----    Residual Diagnostics ------- Histogram - Normality   Test

Serial Correlation 
View ----    Residual Diagnostics ------- Serial Correlation   LM   Test, try   different   lag   1,2,3   …
Breusch-Godfrey   Serial Correlation LM   Test:
Null   hypothesis: No   serial   correlation   at   up   to   1   lag

Breusch-Godfrey   Serial Correlation LM   Test:
Null   hypothesis: No   serial   correlation   at   up   to   2   lags

Heteroskedasticity 
View ----    Residual Diagnostics ------- Heteroskedasticity Tests, Test type: White, untick
Include White cross terms
Heteroskedasticity   Test:   White
Null hypothesis: Homoskedasticity

View ----    Residual Diagnostics ------- Heteroskedasticity Tests, Test type: Breusch-Pagan-   Godfrey
Heteroskedasticity   Test: Breusch-Pagan-Godfrey
Null hypothesis: Homoskedasticity

10. Coefficient Diagnostics tests for OLS Multicollinearity 
View ----    Coefficient Diagnostics ------- Variance Inflation Factors
Variance   Inflation   Factors
Date: 11/01/22       Time: 00:10
Sample: 1   107
Included   observations: 107

11. Interpretation, analysis and discussion 
Is this a reliable regression fit? i.e. the OLS   output in   Step   7   above






         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
