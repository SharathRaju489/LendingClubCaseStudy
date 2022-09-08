# Lending Club Case Study
> In this we basically used EDA to explore the data and realise the factors that could be needed to avoid defaulters for lending club investors.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Lending Club is the largest online loan facilitating marketplace for personal loans, business loans and financing for medical procedures.
- People in need can easily access loans with lower interest rates through their online portal.
- Many of the lending companies goes through credit loss, which is the amount of money lost when the borrower refuses to pay or runs away with the money owed.
- Our agenda here is to analysis the factors which contribute/influence the Defaulted cases, so that we can save the business from huge losses.
- We are using lending club dataset that contains the complete loan data for all loans issued through the time period 2007 to 2011.

## Conclusions
- Loans of 60 terms should be limited for someone with being a defaulter profiler.
- Bank should avoid approving loan for someone with pub rec value >= 5.
- Borrowers for whom the number of inquiries in the last 6 months were >=1 should be not encouraged much.
- Loans for which Interest rates are higher than 12% and above, the investor can expect a higher risk and decide whether to proceed or step back.
- Investors should be very cautious while the loan amounts are above 100k, in possible situations they should be avoided.
- More than 20% of loans taken on purpose of debt consolidation and small business have defaulted so, considering all the above factors for these applicants is very crucial to avoid any losses.
- Approving the lesser than eligible amount for 0-3 years and 10+ experienced applicants would be a better choice as they defaulted the most compared to others.
- Borrowers from grade B, C and D have defaulted more , so considering the important factors that in increases the probability of him being a defaulter should be evaluated thoroughly.
- dti on an average should decrease as the income bar increases. It should preferably be less than 13.7.
- borrowers from AK and TN states should given loan after verified other factors mentioned here.

## Technologies Used
- pandas - version 1.1.3
- numpy - version 1.20.3
- matplotlib - version 3.3.2
- seaborn - version 0.11.0


## Contact
Created by [@tusharsaxena250] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
