## Week 3 : Day 5
Last class, we all learn about vectors (character, numeric & logical) and indexing, naming, subsetting.
Today, we will cover following topics
- vector functions
- selecting vector elements
- matrix
- data.frame
- list


### More on vectors
```{}
# conditions
a <- 1
b <- 2

# equal to
a == b

# not equal to
a != b

# greater than
a > b
# less than
a < b

# greater than equal to
a >= b

# less than equal to
a <= b

#-------
# Maths functions
num_vec <- c(3,2,8,-1)

sum(num_vec)


log(num_vec)

log2(num_vec)

log10(c(10,100,1000))

#-------
# useful functions
# seq function

# sample values from a input
vals <- 1:100


# about set.seed() function; Random Number Generation
# without set.seed() function

samp_data <- sample(x=vals,size=50,replace=TRUE)

# with set.seed() function
set.seed(198)
samp_data <- sample(x=vals,size=50,replace=TRUE)





# Sorting vector
sort(samp_data)

# learn more about sort: ?sort
#---
# reverse a vector
rev(samp_data)
#---
# table function to see counts of values
table(samp_data)

#---
# unique function to see unique values
unique(samp_data)

#---
# selecting vectors

#---
# LOOPS

# for loop

# while loop

#---
# FUNCTIONS

#---
```

### Matrix in R
```{R}
# create a empty matrix with 3 rows and 4 columns

mat <- matrix(data=NA, nrows=3, ncols=4)

# matrix (5x6) with  30 random values
rand_val <- rnorm(n=30,mean=4,sd=10)

rand_mat <- matrix(data=rand_val,nrow=5,ncol=6)

# about set.seed() function; Random Number Generation

set.seed(892)
rand_val_common <- rnorm(n=50,mean=4,sd=10)

rand_mat_common <- matrix(data=rand_val_common,nrow=10,ncol=5)

#--------
# subsetting in matrix
# 1st row
rand_mat_common[1,]

# 1st column 
rand_mat_common[,1]

# more exercise
#--------
# perform some statics like mean, sd 
#--------
# 

#--------
# introduction to apply function
#--------

```
### data.frame in R
```{R}
# convert a matrix into data.frame
rand_df <- data.frame(rand_mat_common)

# add a phenotype

# estimate distance b/w rows

# erstimate distance b/w column


```


