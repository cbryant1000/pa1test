
PA1-test: `testthat`  
=====================
##Unit Tests for Programming Assignment 1

---------------------------------------

This project is an implementation of `testthat` unit tests for the Coursera R Programming course Assignment 1.  The `testthat` package was written by [Hadley Wickham](http://had.co.nz/) to enable unit testing of the 'stringr' string manipulation package during development.  The unit tests implement the examples given in the [Instructions for Programming Assignment 1](https://class.coursera.org/rprog-010/assignment/view?assignment_id=3).

 # | Function Name      | Description                             | `testthat` Script
---|--------------------|------------------------------|---------------------------------------------
 1 | `pollutantmean`         | Calculate the mean of a pollutant | [test-pollutantmean.r](./test-pollutantmean.r)
 2 | `complete` | Report the number of complete cases | [test-complete.r](./test-complete.r)
 3 | `corr`      | Calculate the correlation between two pollutants | [test-corr.r](./test-corr.r)

### Running the `testthat` Scripts  

1. `source` the script for the assignment into your R working environment.  
  + E.g., `> source("pollutantmean.R")`  
2. `source` the matching `testthat` script into your environment.  
  + `> source("test-pollutantmean.r")`  
  + `>`  
  
3. Notice how _unobtrusive_ `testthat` is, if there is no error.  

You can also run scripts using the `test_file` function.
```
> test_file("test-pollutantmean.r")
Calculate the mean of a pollutant across a specified list of monitors : .....

> 
```

A _little_ more verbose, but still pretty quiet.

### More Information 

For more information on the `testthat` package see,

-  [testthat: Get Started with Testing](http://journal.r-project.org/archive/2011-1/RJournal_2011-1_Wickham.pdf), _R Journal_, June 2011.  
- [CRAN package, testthat](http://cran.r-project.org/web/packages/testthat/index.html)

-----
