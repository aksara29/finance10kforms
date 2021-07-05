# finance10kforms
Sentiment analysis and topic modelling including data scrapping from EDGAR.
If you want to reproduce the result based on the analysis provided, please use rmd instead of a html file.

Note that there is a bug when knitting r markdown into .html, specifically for stm(), which is STM model estimation.
In addition, due to the bug, the prevalence estimation is changed from using splines, s() i.e., non-linear function, to linear for the variable 'year'. 
Hence, the result in the section is inappropriate. 
