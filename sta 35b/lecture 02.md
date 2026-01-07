learning goals

explain what tabular data means
describe the role of tidyverse
explain what a tibble is
extract variables correctly from a dataset
explain why tibbles are strict


![[Pasted image 20260107131817.png]]

install.packages("package name")
load package -> library("package name")

everytime you reload R, you have to reinstall/reload the packages

tidyverse.org -> collection of 34 R packages

install.packages("tidyverse")
library("tidyverse")

tidyverse is:
- designed for data analysis workflows
- consistent syntax across packages
- encourages readable code
- reduces silent errors

Tabular data

data in tabular structure (rectangular shape)
- rows = observations (cases)
- columns = variables (features)
- one value per cell
- each column has a clear meaning


what is a tibble
 - a modern version of a data.frame
 - stores the same data
 - behaves more safely
 - core data structure in tidyverse
 - more details: vignette("tibble")

creating tibbles
- ways to create tibbles:
	- tibble(): create from vectors
		- vectors must have same class (all strings, all integers)
	- as_tibble(): convert existing data frame
	- tribble(): transpose+tibble, creates row by row.

data.frame vs tibble
- same data
- different behavior
	- printing behaviors are very different
	  - when you type tibble, shows first 10 rows
	  - shows colums that fit on screen
	  - displays column names and types
	  - avoids overwhelming output
	  - avoids overwhelming output
		  - print(), options(), View()

subsetting: 
- df %>% . $x
- $ extracts a vector
- [[]] 

reading data into R
- data import
- real data comes from files
- csv, tsv, fixed-width formats
- tidyverse uses read r
	- advantages of readr
		- faster
			- try data.table::fread()
		- produces tibbles by default
		- consistent behavior
		- better error messages
			- predictable behavior leads to reproducible analysis
read_csv("a, b ,c
1,2,.", na = ".")

