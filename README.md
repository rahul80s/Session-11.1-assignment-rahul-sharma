# Session-11.1-assignment-rahul-sharma
Acagild session 11.1 assignment 

1. Use the given link and locate the bank marketing dataset. Data Set Link

Perform the below operations:

a. Create a visual for representing missing values in the dataset.

b. Show a distribution of clients based on a Job.

c. Check whether is there any relation between Job and Marital Status?

d. Check whether is there any association between Job and Education?

Ans 1 ->

a. ->

read.csv(bank-additional.csv, header=t, sep=",")

bank-additional [bank-additional=="unknown"] <- NA

b. ->

barplot(counts,col=c("green","yellow"),legend = rownames(counts), main = "Job")

c. ->

No

d. ->

Yes
