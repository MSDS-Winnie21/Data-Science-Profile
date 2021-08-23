[DataScientist.csv](https://github.com/MSDS-Winnie21/Data-Science-Profile/files/7034502/DataScientist.csv)
# Data-Science-Profile

example1= read.csv(file.choose(), header = TRUE)
example1$Salary.Estimate


#using the summary function 
summary(DataScientist$`Salary Estimate`)

DataScientist$salaryFact = as.factor(DataScientist$`Salary Estimate`)
head(DataScientist)
summary(DataScientist$salaryFact)

barplot(summary(DataScientist$salaryFact), main = "Data Scientist Salary", ylab = "Salary", xlab = "Data scientist")

