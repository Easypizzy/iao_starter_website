---
date: "2023-07-26"
output: html_document
status: "offline"
---



**DATA UNDERSTANDING FOR ANALYSIS**

  A Data set in table format consists of rows and column of which the first rows in the data sets is the *column names* and the first column is the *row names*.
  Each rows in the table is called *an observation*. Also, the first row, which consists of the *column names*, is the names of the variable from the data set. Each column explains or shows how the variable changes with each observation. Let us observe the table below **[fig 1.0]**
  


```r
dataset1
```

```
##        var_1 var_2 var_3
## Obsv_1    11    BA    31
## Obsv_2    12    AA    32
## Obsv_3    13    AA    33
## Obsv_4    14    AB    34
```


```r
# NB:- Column names = names of each variable in each column of the data set.
# NB:- Each column explains the change in each variable wrt each observation
```

**PERFORMING SIMPLE DATA ANALYSIS**

  To select certain variables for analysis, use the **select()** for selecting. Before we can use this function, we need to be sure to have **tidyverse** package installed in our R or Rstudio and then call the package;
 

```r
library(tidyverse)
```

```
## -- Attaching core tidyverse packages ------------------------ tidyverse 2.0.0 --
## v dplyr     1.1.2     v readr     2.1.4
## v forcats   1.0.0     v stringr   1.5.0
## v ggplot2   3.4.2     v tibble    3.2.1
## v lubridate 1.9.2     v tidyr     1.3.0
## v purrr     1.0.1     
## -- Conflicts ------------------------------------------ tidyverse_conflicts() --
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
## i Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors
```

Using the *select()*, let us say we want the first and third variable in our data sets. That is, var_1 and var_3, we use the select function select them. The select function is one of the basic syntax for *dplyr package* under *tidyverse package*. We also have other basic syntax like *mutate()*, *filter()*, *arrange()*, and *summarize()*. Check below;



I can both select and filter my data set.
check <http://Israel045/israelbinnarchv.netlify> for more data for practice. Thanks.

