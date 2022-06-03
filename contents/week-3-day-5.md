## Week 2 : Day 5
Last class, we all learn about vectors (character, numeric & logical) and indexing, naming, subsetting.
Today, we will cover following topics
- matrix
- data.frame
- list

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


