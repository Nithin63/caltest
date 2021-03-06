# IS601-CalculatorProject
### IS601 MiniProject #2 - Calculator
#### Contributors: Harrison Lu and Roberto Rivera

[![Build Status](https://travis-ci.com/hl533/IS601-CalculatorProject.svg?branch=master)](https://travis-ci.com/hl533/IS601-CalculatorProject)

This project will have 2 parts:

Basic Calculations:
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Square
6. Square Root

Statistical Functions: 

[Link to References Directory](https://github.com/hl533/IS601-CalculatorProject/tree/master/References)

- [x] Population Mean
- [x] Median
- [x] Mode
- [x] Population Standard Deviation
- [x] Variance of population proportion
- [x] Z-Score
- [x] Population Correlation Coefficient
- [x] Confidence Interval
- [x] Population Variance
- [x] P Value
- [x] Proportion
- [x] Sample Mean
- [x] Sample Standard Deviation
- [x] Variance of sample proportion

This uses both built-in functions and CSV data sheets to test the 
functionality of the calculator.


### References:
1. http://www.mbaexcel.com/excel/how-to-create-a-normally-distributed-set-of-random-numbers-in-excel/
2. https://www.geeksforgeeks.com


### Changelog:
[Log.csv](log.csv)

|Hash    |User          |Date and Time                  |Change                                                                                                                            |
|--------|--------------|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
|af6d687 |hl533         |Wed, 20 Nov 2019 19:49:42 -0500|FEATURE: P-Value                                                                                                                  |
|f07fd2b |hl533         |Wed, 20 Nov 2019 19:22:02 -0500|TASK: Z-Score test now completing successfully                                                                                    |
|4.77E+06|hl533         |Wed, 20 Nov 2019 18:23:36 -0500|FEATURE: Sample Mean, Sample Std Dev, and Sample Variance features and tests complete                                             |
|368b6ea |hl533         |Wed, 20 Nov 2019 16:40:37 -0500|FEATURE: Confidence Interval features and tests completed                                                                         |
|5f35f65 |hl533         |Wed, 20 Nov 2019 16:09:58 -0500|FEATURE: Variance of Population Proportion feature and tests complete                                                             |
|d5d2d05 |hl533         |Wed, 20 Nov 2019 15:24:33 -0500|FEATURE: Population Correlation Coefficient feature and tests complete                                                            |
|306c32f |hl533         |Wed, 20 Nov 2019 14:19:41 -0500|TASK: I think Z-score works? But the runtime is 5 minutes. Why?                                                                   |
|429f23e |hl533         |Wed, 20 Nov 2019 12:00:08 -0500|FEATURE: Created Z-Score function? I think it's broken                                                                            |
|15ed531 |hl533         |Wed, 20 Nov 2019 11:23:13 -0500|FEATURE: Proportion function and test fully working                                                                               |
|7bab156 |hl533         |Tue, 19 Nov 2019 11:07:10 -0500|FEATURE: Variance and Standard Deviation functions and tests now fully working with new method                                    |
|b7b5355 |hl533         |Tue, 19 Nov 2019 07:04:15 -0500|FEATURE: Completely redid stastistics functions and tests to allow for testing of full populations                                |
|d5d34eb |hl533         |Fri, 15 Nov 2019 14:52:36 -0500|TASK: Added another normally distributed population/sample set to test                                                            |
|cbd810f |hl533         |Fri, 15 Nov 2019 13:44:22 -0500|FEATURE: Variance Calculator and Test now functional                                                                              |
|0db5684 |hl533         |Fri, 15 Nov 2019 13:43:56 -0500|FEATURE: Standard Deviation Calculator and Test now functional                                                                    |
|558f8be |hl533         |Fri, 15 Nov 2019 11:49:36 -0500|FEATURE: Mode Calculator and Test now functional                                                                                  |
|b384358 |hl533         |Fri, 15 Nov 2019 11:14:47 -0500|EDIT: Median test running now                                                                                                     |
|792ac9e |hl533         |Wed, 13 Nov 2019 18:31:40 -0500|FEATURE: Median function and test running, but some kind of math error                                                            |
|aec42ff |hl533         |Wed, 13 Nov 2019 15:19:36 -0500|FEATURE: MEAN TEST WORKING NOW!                                                                                                   |
|4e33ea4 |hl533         |Wed, 13 Nov 2019 14:48:10 -0500|TASK: Still getting errors, but added decorator info                                                                              |
|66b5108 |hl533         |Mon, 11 Nov 2019 12:31:34 -0500|EDIT: Still getting errors, plus a typo change                                                                                    |
|b4ad250 |hl533         |Sat, 9 Nov 2019 11:28:32 -0500 |EDIT: Still getting errors, but wanted remote up-to-date                                                                          |
|fa41f7c |hl533         |Sat, 9 Nov 2019 11:00:10 -0500 |TASK: Simplified UnitTestStats.csv and continuing to get error: cannot add int and collections.orderedDict""                      |
|4e2b089 |hl533         |Sat, 9 Nov 2019 10:57:48 -0500 |TASK: Simplified UnitTestStats.csv and continuing to get error: cannot add int and collections.orderedDict""                      |
|279f14c |Roberto Rivera|Fri, 8 Nov 2019 12:32:47 -0500 |Task: Added link for Reference Directory to README.md                                                                             |
|e8388c6 |hl533         |Thu, 7 Nov 2019 18:38:35 -0500 |TASK: Fixed test_StatisticsTests.py statistics filepath reference, so that error is fixed. New errors now.                        |
|8bf1646 |hl533         |Wed, 6 Nov 2019 20:17:57 -0500 |TASK: Added travis-ci status icon to README.md                                                                                    |
|17760da |hl533         |Wed, 6 Nov 2019 20:11:45 -0500 |TASK: Added requirements.txt per travis-ci.com                                                                                    |
|a944eba |hl533         |Wed, 6 Nov 2019 20:09:14 -0500 |FEATURE: Added Mean calculations to statistics, as well as travis files                                                           |
|9af1b59 |hl533         |Wed, 6 Nov 2019 18:16:43 -0500 |TASK: Began attempting to do mean in statistics                                                                                   |
|de03882 |hl533         |Mon, 4 Nov 2019 12:47:26 -0500 |TASK: Removed UnitTestAll.csv and references, and added StatisticsTest.py                                                         |
|deeba13 |hl533         |Mon, 4 Nov 2019 12:13:31 -0500 |TASK: Cleaned up CalculatorTests and UnitTests for better consistency                                                             |
|a42ff08 |hl533         |Sun, 3 Nov 2019 11:51:30 -0500 |FEATURE: Got the CalculatorTests and CsvTests to work! Had to rename the tests to test_                                           |
|f0ccbea |hl533         |Sun, 3 Nov 2019 11:43:44 -0500 |TASK: Again matching up basiccalculator to Prof's template, including the individual calculation.py docs                          |
|a1434b2 |hl533         |Sun, 3 Nov 2019 09:43:45 -0500 |TASK: Matching up basiccalculator to Prof's template                                                                              |
|4d534d2 |Roberto Rivera|Sat, 2 Nov 2019 16:53:46 -0400 |Feature: Added the VarianceofSampleProportion.md file. Explained the function and how it's calculated.                            |
|27d113d |Roberto Rivera|Sat, 2 Nov 2019 16:52:41 -0400 |Feature: Added The PopulationVariance.md file. Defined how the function is calculated.                                            |
|1dd62e7 |Roberto Rivera|Sat, 2 Nov 2019 16:49:37 -0400 |Fix: Edited The PopulationVariance.md file.                                                                                       |
|302a69b |Roberto Rivera|Sat, 2 Nov 2019 16:48:19 -0400 |Fix: Added the VarianceofSampleProportion.md file. Defines and shows how to complete the function.                                |
|93fb39e |Roberto Rivera|Sat, 2 Nov 2019 16:45:49 -0400 |Fix: Added the PopulationVariance.md file. Defines and shows how to complete the function.                                        |
|15866d4 |Roberto Rivera|Sat, 2 Nov 2019 16:43:42 -0400 |Feature: Added the SampleStandardDeviation.md file. Defines and shows how to complete the function.                               |
|b0c5ae7 |Roberto Rivera|Sat, 2 Nov 2019 16:41:16 -0400 |Feature: Added the SampleMean.md file. Defines and shows how to complete the function.                                            |
|df07d89 |Roberto Rivera|Sat, 2 Nov 2019 16:34:59 -0400 |Feature: Added the Proportion.md file. Defines and shows how to complete the function.                                            |
|87612a4 |Roberto Rivera|Sat, 2 Nov 2019 16:28:34 -0400 |Feature: Added the PValue.md file. Defines and shows how to complete the function.                                                |
|c4ebb96 |Roberto Rivera|Sat, 2 Nov 2019 16:18:40 -0400 |Feature: Added the PopulationVariance.md file. Defines and shows how to complete the function.                                    |
|7e4372e |Roberto Rivera|Sat, 2 Nov 2019 15:58:29 -0400 |Feature: Added the ConfidenceInterval.md file. Defines and shows how to complete the function.                                    |
|2f9065d |Roberto Rivera|Sat, 2 Nov 2019 15:55:07 -0400 |Feature: Added the ConfidenceInterval.md file. Defines and shows how to complete the function.                                    |
|87aef33 |Roberto Rivera|Sat, 2 Nov 2019 15:48:55 -0400 |Feature: Added the PopulationCorrelationsCoefficient.md file. Defines and shows how to complete the function.                     |
|9a508ff |Roberto Rivera|Sat, 2 Nov 2019 15:36:15 -0400 |Feature: Added the Standardized_Zscore.md file. Defines and shows how to complete the function.                                   |
|2b6e1a4 |Roberto Rivera|Sat, 2 Nov 2019 15:27:06 -0400 |Feature: Added the VarianceofPopulationProportion.md file. Defines and shows how to complete the function.                        |
|01e2e6a |hl533         |Sat, 2 Nov 2019 15:26:06 -0400 |TASK: Added a reference section in README                                                                                         |
|691bb8d |Roberto Rivera|Sat, 2 Nov 2019 15:24:08 -0400 |Feature: Added the PopulationStandardDeviation.md file. Defines and shows how to complete the function.                           |
|5f3a05c |Roberto Rivera|Sat, 2 Nov 2019 15:20:35 -0400 |Feature: Added the Mode.md file. Defines and shows how to complete the function.                                                  |
|26eeafa |Roberto Rivera|Sat, 2 Nov 2019 15:14:04 -0400 |Feature: Added the Populationmean.md file. Defines and shows how to complete the function.                                        |
|d60839b |Roberto Rivera|Sat, 2 Nov 2019 15:13:47 -0400 |Feature: Added the Median.md file. Defines and shows how to complete the function.                                                |
|bfc7a92 |Roberto Rivera|Sat, 2 Nov 2019 15:08:16 -0400 |Feature: Added the PopulationMean.md file. Defines and shows how to complete the function.                                        |
|76c9215 |Roberto Rivera|Sat, 2 Nov 2019 14:46:34 -0400 |Feature: Added the PopulationMean.txt file. Defines and shows how to complete the function.                                       |
|4d4d004 |Roberto Rivera|Sat, 2 Nov 2019 14:39:20 -0400 |Task: Added Tests Directory with __init__.py file                                                                                 |
|6c79d63 |Roberto Rivera|Sat, 2 Nov 2019 14:38:45 -0400 |Task: Added Statistics Directory with Statistics.py file                                                                          |
|fbbf7da |Roberto Rivera|Sat, 2 Nov 2019 14:38:00 -0400 |Task: Added Fileutilities Directory with absolutepath.py file                                                                     |
|bfb7d8b |Roberto Rivera|Sat, 2 Nov 2019 14:37:06 -0400 |Task: Added CsvReader Directory with CsvReader.py and __init__.py files                                                           |
|d0b42b6 |Roberto Rivera|Sat, 2 Nov 2019 14:36:18 -0400 |Task: Add Calculator Directory with Calculator.py and __init__.py files                                                           |
|6d81432 |Roberto Rivera|Sat, 2 Nov 2019 14:35:31 -0400 |Task: Add Calculator Directory with Calculator.py and __init__.py files                                                           |
|5276dda |hl533         |Sat, 2 Nov 2019 14:14:57 -0400 |TASK: Started making revisions to Calculator.py and added UnitTestStats csv with sample normal distribution                       |
|c10a161 |hl533         |Sat, 2 Nov 2019 10:36:34 -0400 |TASK: Revised Master Branch and README.md to reflect current iteration of the project: Stastical Calculations.                    |
|7434307 |hl533         |Fri, 1 Nov 2019 12:21:37 -0400 |TASK: For organization purposes, placed original UnitTest csvs into separate folder                                               |
|759d05c |hl533         |Fri, 1 Nov 2019 12:16:22 -0400 |TASK: Added a Changelog                                                                                                           |
|05293b8 |hl533         |Fri, 1 Nov 2019 11:51:05 -0400 |EDIT: Made minor spacing/formatting changes per recommendation of pycharm to comply with Python standards.                        |
|ba826c7 |hl533         |Thu, 31 Oct 2019 20:38:48 -0400|TASK: Created basic README file                                                                                                   |
|eedc56f |hl533         |Thu, 31 Oct 2019 20:32:55 -0400|FEATURE: Modified individual csv tests within calculatortests.py. tests run successfully now.                                     |
|b8c51ba |hl533         |Thu, 31 Oct 2019 20:19:27 -0400|FEATURE: Inserted each csv test back from the CsvTestCodes.txt file back into CalculatorTests.py                                  |
|80a5dd2 |hl533         |Thu, 31 Oct 2019 20:14:11 -0400|FEATURE: Combined all csvs into single master UnitTest csv                                                                        |
|db7b8f7 |hl533         |Thu, 31 Oct 2019 17:16:00 -0400|FEATURE: Added and tested each CSV Test Code and stored in CSVTestCodes.txt file. Made modifications to csv files for consistency.|
|6a889a2 |hl533         |Thu, 31 Oct 2019 15:04:33 -0400|TASK: Modified Subtraction CSV Test in calculatortests.py. Was missing a Row(). Now working.                                      |
|318f2a2 |hl533         |Thu, 31 Oct 2019 03:28:15 -0400|TASK: Added CsvTests and UnitTestSubtraction files, and added code to try to start using csvs in tests. Not working yet           |
|b9cdb0e |hl533         |Fri, 25 Oct 2019 08:58:26 -0400|TASK: Added CsvReader file, edited files to no longer try to use pandas, and to use csvreader instead                             |
|86e4e8b |hl533         |Fri, 18 Oct 2019 15:00:23 -0400|TASK: Added UnitTest Files                                                                                                        |
|eb133cd |hl533         |Fri, 18 Oct 2019 14:52:51 -0400|FEATURE: Added Multiplication, Division, Square, and Square Root calculator functions and tests                                   |
|771b342 |hl533         |Thu, 17 Oct 2019 14:51:06 -0400|EDIT: added a missing line of code to CalculatorTests.py                                                                          |
|1cc44cb |hl533         |Thu, 17 Oct 2019 14:41:10 -0400|FEATURE: Created and wrote code for Dockerfile, Calculator.py and CalculatorTests.py                                              |
|3ff491f |hl533         |Thu, 17 Oct 2019 12:45:41 -0400|Task: Calculator from class made in Colab                                                                                         |
|a8da4ad |hl533         |Thu, 17 Oct 2019 12:09:04 -0400|Initial commit                                                                                                                    |
