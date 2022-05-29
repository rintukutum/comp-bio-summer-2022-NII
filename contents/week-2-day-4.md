## Week 2 : Day 4
Last class, we all learn a bit about [R project](https://www.r-project.org). Ended our session with the downloading R from [CRAN](https://cran.r-project.org) (Comprehensive R Archive Network) and installed R in Windows. We got introduced into R interface, "hello world to R", a few best practices to code in R. 

Today, we will try to cover the R-basics. 
- Objects in R
- Naming objects in R
- Reassigning object names or deleting objects
- Understanding object data types
- Mathematical and functional operations on objects
- Data types and structures
- About vectors
	- Numerical vectors
	- Character vectors
	- Logical vectors
## Vectors
```{R}
hello <- function(){
  print('Hello World')
}

hello2 <- function(){print('Hello World')}


# this is a comment

# this is a character vector with 
# a single element
 
gene_name <- "tp53"

# numerical vector with one element
a <- 1

b <- 10

# sum or addition
a + b

# length is a function
length(a)

# our fav. gene names
gene_names <- c('RPOB','PARP1','RXR', 'P21','ZEB2','CASPAS','PSPA', 
'GAP2','GNLY','IRF2','BLIMP','DPP4','HSP90','INF3','RELB','RV0096')

# scholar names
scholar_name <- c('ARCHANA', 'WITTY', 'AZAD', 'TAVLEEN', 'SONANJALI', 
'KOMAL', 'DEVENDAR', 'JASLEEN', 'RONAK', 'ANSHUL', 'JABI', 'ATHAR', 
'ARNAB', 'MANJU', 'NAVEEN', 'MOHIT')

# subset vector with index
gene_names[c(3,10)]

# names is a function to check any name associated with the element
names(gene_names)

# assign names to fav gene with scholar name
names(gene_names) <- scholar_name

# now we can use the name of the scholar to access the value (gene)
gene_names['MANJU']

# we will take a smaller toy example to understand above
genes <- c('A', 'B', 'C')
genes[2]
double_name <- c('aa', 'bb', 'cc')

pathway_x <- c('aa','cc')

names(genes) <- double_name

# short cut for name and value pair
XYZ <- c(xx = 'X', yy = 'Y', zz = 'Z')

## LOGICAL VECTOR

LG <- c(TRUE,FALSE,TRUE)

genes[LG]

!LG

genes[!LG]



```
## Good Pactices
- [Good practices in R programming](https://kb.iu.edu/d/aaxp)
- [Best practices](https://db.rstudio.com/best-practices/)
- [Good Practices in R Programming by Martin Machler](https://stat.ethz.ch/Teaching/maechler/R/useR_2014/Maechler-2014-pr.pdf)

## Composite figures
- [Inkscape](https://inkscape.org)
- [Inkscape Explained in 5 Minutes](https://www.youtube.com/watch?v=pa6a7oz7vEE)
- [All 21 Inkscape Tools Explained in 10 Minutes](https://www.youtube.com/watch?v=qq7HsMvEVmU)

## Editor
- [notepad++](https://notepad-plus-plus.org)


 
