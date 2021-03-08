## Information & Introduction

The dataset included herein was created as part of a course in the MLIS program at the University of Washington iSchool. Compiling data provided by the Washington Office of Superintendant of Public Instruction (WOSPI) and the Office of Financial Management (WSOFM), these data examine the total number of homeless K-12 students in Washington state compared against yearly enrollment, as well as identifying the individual homeless student statistics in King, Pierce, Snohomish, Spokane, and Yakima counties, as they consistently accounted for the largest homeless student count figures across surveyed years. Also included are the number of homeless students statewide, per count, identified as students with disabilities, unaccompanied youth, or English-language learners, emphasizing additional, crucial need within homeless student populations. 

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
| **hsc_KingC** | Homeless student count King County | Integer | Any number ≥ 0 | Sum of homeless K-12 students in King County from the indicated survey year (from WOSPI surveys).  |
| **hsc_PierceC** | Homeless student count Pierce County | Integer | Any number ≥ 0 | Sum of homeless K-12 students in Pierce County from the indicated survey year (from WOSPI surveys). |
| **hsc_SnohomishC** | Homeless student count Snohomish County | Integer | Any number ≥ 0 | Sum of homeless K-12 students in Snohomish County from the indicated survey year (from WOSPI surveys). |
| **hsc_SpokaneC** | Homeless student count Spokane County | Integer | Any number ≥ 0 | Sum of homeless K-12 students in Spokane County from the indicated survey year (from WOSPI surveys). |
| **hsc_YakimaC** | Homeless student count Yakima County | Integer | Any number ≥ 0 | Sum of homeless K-12 students in Yakima County from the indicated survey year (from WOSPI surveys). |
| **hst_WA_State** | Homeless student total Washington State | Integer | Any number ≥ 0 | Total number of homeless K-12 students in Washington State (all counties) from the indicated survey year (from WOSPI surveys). |
| **te_WA_State** | Total K-12 enrollment Washington State | Integer | Any number ≥ 0 | Total number of K-12 students enrolled in Washington State schools from the indicated survey year (from WSOFM reports).  |
| **%homeless_SW** | Percent of students homeless statewide | Percentage | 0% - 100% | Percentage of students classed as homeless in a surveyed year. Calculated by dividing the year's value for hst_WA_State (from WOSPI surveys) by the same year's te_WA_State (from WSOFM reports). |
| **swt_hs_Disabled** | statewide total Disabled homeless students | Integer | Any number ≥ 0 | Total number of homeless students in Washington State identified as students with disabilities from the indicated survey year (from WOSPI surveys). |
| **swt_hs_ELL** | statewide total English Language Learner homeless students | Integer | Any number ≥ 0 | Total number of homeless students in Washington State identified as English Language Learners from the indicated survey year (from WOSPI surveys). |
| **swt_hs_UY** | statewide total Unaccompanied Youth homeless students | Integer | Any number ≥ 0 | Total number of homeless students in Washington State identified as Unaccompanied Youth from the indicated survey year (from WOSPI surveys). |

## Metadata
Schema Used: Project Open Data


| **Attribute** | **Value** |
| --- | --- |
| title | Washington State Homeless Students |
| accessLevel | public |
| contactPoint | Em Craig | [mailto:emcraig@uw.edu](mailto:emcraig@uw.edu) |
| describedBy | [https://https://github.com/emcraig/WS-homeless-students](https://github.com/emcraig/WS-homeless-students) |
| description |  These data examine the number of homeless K-12 students in Washington state compared against yearly enrollment, identify individual statistics in King, Pierce, Snohomish, Spokane, and Yakima counties, and high-risk students with additional needs within the homeless population. The audience for this dataset is Washington State policymakers and the public. Created as part of a UW iSchool Course, Winter 2021.|
| accessURL | [https://github.com/emcraig/WS-homeless-students/blob/main/hsc-WS_2015-2019.csv](https://github.com/emcraig/WS-homeless-students/blob/main/hsc-WS_2015-2019.csv) |
| downloadURL | [https://github.com/emcraig/WS-homeless-students/blob/main/hsc-WS_2015-2019.xlsx](https://github.com/emcraig/WS-homeless-students/blob/main/hsc-WS_2015-2019.xlsx)
| format | CSV & XLSX |
| mediaType | CSV & XLSX |
| keywords (tags) | homelessness, homeless students, K-12, education, at-risk youth |
| issued | 2021-03-05 |
| keyword | &quot;recycling&quot;, &quot;diversion&quot;, &quot;palo alto&quot;, &quot;seattle&quot;, &quot;san francisco&quot;, &quot;washington&quot;, &quot;california&quot; |
| landingPage | [https://https://github.com/emcraig/WS-homeless-students](https://https://github.com/emcraig/WS-homeless-students) |
| language | EN-US |
| modified | 2021-03-08 |
| publisher | Em Craig |
| related documents | Washington Office of Superintendent of Public instruction datasets:
[https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202019HomelessGradeLevel%28County_Suppressed%29.xlsx](https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202019HomelessGradeLevel%28County_Suppressed%29.xlsx)
[https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202018HomelessGradeLevel%28County_Suppressed%29.xlsx](https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202018HomelessGradeLevel%28County_Suppressed%29.xlsx)
[https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202017HomelessGradeLevel%28County_Suppressed%29.xlsx](https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202017HomelessGradeLevel%28County_Suppressed%29.xlsx)
[https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202016HomelessGradeLevel%28County_Suppressed%29.xlsx](https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202016HomelessGradeLevel%28County_Suppressed%29.xlsx)
[https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202015HomelessGradeLevel%28County_Suppressed%29.xlsx](https://www.k12.wa.us/sites/default/files/public/homelessed/pubdocs/Copy%20of%202015HomelessGradeLevel%28County_Suppressed%29.xlsx)

Washington State Office of Financial Management Enrollment report(s):
[https://ofm.wa.gov/washington-data-research/statewide-data/washington-trends/budget-drivers/kindergarten-through-grade-12-k-12-enrollment](https://ofm.wa.gov/washington-data-research/statewide-data/washington-trends/budget-drivers/kindergarten-through-grade-12-k-12-enrollment)
| rights | All data represented in this dataset are freely accessible to the public, as they are hosted here on gitHub and any respective source organizations. |


## Contact
Em Craig
emcraig@uw.edu

## Security

These data are freely available to the public.
