# Lending_Club_CaseStudy

> The case study aims to determine the driver variables that cause default on a loan,
  by analysing the dataset provided by the lender Lending_Club



## Table of Contents

* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


<!-- You can include any other section that is pertinent to your problem -->

## General Information

The project aims to find the key variables that drive a borrower to default on a loan,
and hence mititgate the issuance of such loans.

The dataset is obtained from one of the largest online lenders "LendingClub" for the years 2007 through 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

the primary driving variables that lead to default are int_rate, revol_util (the percentage of credit used by borrower), 
loan_amnt, term of loan, verification status of borrower, Home ownership status.

The interest rate of defaulters on its own is 20% higher than borrowers who successfully repay.

55% seems to be the median revol_util above which the borrowers start defaulting,
 regardless of whether they own a home, mortgaged or are rented

The loans of tenure 60 months default less, but this could be further improved if the high int_rate of around 16% is reduced, 
this will also encourage more borrowers to go form longer termed loans.

verified borrowers should typically not default but here they default as much as the non verified borrowers, 
this is because they are being given on average 100% more loan amount and on a higher interest rate which is leading to more default


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- jupyter - version 3.9.13
- Visual studio code - version 1.83.0
- git - version 2.42.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@LEANDERANTONY] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->