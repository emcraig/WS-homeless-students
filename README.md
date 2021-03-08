## Information & Introduction

The dataset included herein was created as part of a course in the MLIS program at the University of Washington iSchool. Compiling data provided by the Washington Office of Superintendant of Public Instruction and the Office of Financial Management, these data examine the total number of homeless K-12 students in Washington state compared against yearly enrollment, as well as identifying the individual homeless student statistics in King, Pierce, Snohomish, Spokane, and Yakima counties, as they consistently accounted for the largest homeless student count figures across surveyed years. Also included are the number of homeless students statewide, per count, identified as students with disabilities, unaccompanied youth, or English-language learners, emphasizing additional, crucial need within homeless student populations. 

The foremost intended audience for these data are policymakers, however the dataset is freely available to the public and intended to be readable and useful to citizens, especially of Washington State and the aforementioned counties. It is presented in both **.csv** and **.xls** formats for download.


## File Name(s)

The dataset file(s) are named in the following format:

      _datatype-region_yeardaterange_
      
_datatype_ refers to the type of data represented. for this application, the datatype is 'hsc' or Homeless Student Count.
_region_ refers to the origin of the data or the geographic area it represents. for this application, the region is 'WS' or Washington State.
_yeardaterange_ refers to the period of time the gathered data covers, in years. for this application, the yeardaterange was '2015-2019'.

This file could be updated as a living document, with the latter year in the date range being updated to reflect the most recently added added data. However, it may also be beneficial to maintain profiles of this data in specificied year ranges (5 compiled years/10 compiled years). If and when additional data is added, the **metadata**, **filename**, and **keywords** should be updated to reflect these additions. 

## Data Dictionary


| **Variable** | **Variable Name** | **Measurement Unit** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **survey_Year** | Survey Year | Date | Year / YYYY | Year of the conducted homeless student count |
| **hsc_KingC** | Metal Tonnage | Numerical | Integers greater than 0 | Total tonnage of metal recycled in 2017 (from city reports), different metal types added into single value |
| **hsc_PierceC** | Paper Tonnage | Numerical | Integers greater than 0 | Total tonnage of paper recycled in 2017 (from city reports), different paper types added into single value |
| **hsc_SnohomishC** | Plastic Tonnage | Numerical | Integers greater than 0 | Total tonnage of plastic recycled in 2017 (from city reports), different plastic types added into single value |
| **hsc_SpokaneC** | Average Cost per Ton | Numerical | Numbers greater than 0 (USD) | Averaged cost in USD of recycling a ton of materials in 2017 (from city reports) |
| **hsc_YakimaC** | Diversion Rate | Numerical | Numbers between 0-100 (percentage) | Total percentage of diverted landfill materials in 2017, pulled directly from report |
| **hst_WA_State** | Population Size | Numerical | Integers greater than 0 | Population size in people (Census) |
| **te_WA_State** | Area | Numerical | Numbers greater than 0 (miles squared) | Area of city in miles squared (Census)  |
| **%homeless_SW** | ZScore of Metal Tonnage | Numerical | Any number | ZScore of total tonnage of metal recycled in 2017 (from city reports), different metal types added into single value |
| **swt_hs_Disabled** | ZScore of Paper Tonnage | Numerical | Any number | ZScore of total tonnage of paper recycled in 2017 (from city reports), different paper types added into single value |
| **swt_hs_ELL** | ZScore of Plastic Tonnage | Numerical | Any number | ZScore of total tonnage of plastic recycled in 2017 (from city reports), different plastic types added into single value |
| **swt_hs_UY** | ZScore of Average Cost per Ton | Numerical | Any number | ZScore of averaged cost of recycling a ton of materials in USD in 2017 (from city reports) |

## Metadata
Schema Used: Project Open Data


| **Attribute** | **Value** |
| --- | --- |
| accessLevel | public |
| accrualPeriodicity | R/P1Y |
| fn | Em Craig |
| hasEmail | [mailto:emcraig@uw.edu](mailto:emcraig@uw.edu) |
| describedBy | [https://https://github.com/emcraig/WS-homeless-students](https://github.com/emcraig/WS-homeless-students) |
| description |  These data examine the number of homeless K-12 students in Washington state compared against yearly enrollment, identify individual statistics in King, Pierce, Snohomish, Spokane, and Yakima counties, and high-risk students with additional needs within the homeless population. The audience for this dataset is Washington State policymakers and the public. Created as part of a UW iSchool Course, Winter 2021.|
| accessURL | [https://github.com/emcraig/WS-homeless-students/blob/main/hsc-WS_2015-2019.csv](https://github.com/emcraig/WS-homeless-students/blob/main/hsc-WS_2015-2019.csv) |
| format | CSV |
| mediaType | CSV |
| issued | 2020-03-15 |
| keyword | &quot;recycling&quot;, &quot;diversion&quot;, &quot;palo alto&quot;, &quot;seattle&quot;, &quot;san francisco&quot;, &quot;washington&quot;, &quot;california&quot; |
| landingPage | [https://https://github.com/emcraig/WS-homeless-students](https://https://github.com/emcraig/WS-homeless-students) |
| language | en-us |
| modified | 2021-03-08 |
| publisher | Em Craig |
| Rights | All data represented in this dataset are freely accessible to the public, as they are hosted here on gitHub and any respective source organizations. |
| temporal | 2020/P1Y |
| theme | homelessness, homeless students, K-12, education, at-risk youth |
| title | Washington State Homeless Students |

## Referenced Datasets & Sources



## Contact
Em Craig
emcraig@uw.edu

## Security

These data are freely available to the public.
