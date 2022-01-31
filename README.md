# School District Analysis

## Overview of Analysis
The purpose of this analysis was to aid Maria in her research as a data scientist for a city school district. Through our research, she was able to better prepare her analysis on standardized testing data, funding, and create a general district summary for reports that would provide insight on perfromance trends and patterns--this information would ultimately be used to inform discussions and strategic decisions at the school and district level. Moreover, we were then tasked with analyzing potential academic dishonesty in a particular grade and school, 9th grade at Thomas High School, to determine the extent to which this dishonesty could have affected the data used for the district summary.

## Results
- How is the district summary affected?
In analyzing the potential academic dishonesty focused around the 9th graders at Thomas High School data, we replaced those associated values with NaN to see to what extent they might have influenced the overall results of the analysis, and therefore, decreased its accuracy. When those values were replaced, this surprisngly did not impact the district summary by much.

Below, are the original values:
![This is an image](https://github.com/leilacf/School_District_Analysis/blob/main/original%20district%20summary.png)

Moreover, these are the values after the data was altered:
![This is an image](https://github.com/leilacf/School_District_Analysis/blob/main/challenge%20district%20summary.png)

Although the difference is quite small, after replacing the values with NaN, the average reading score remained the same, while all other categories decreased by 0.01-0.03%.

- How is the school summary affected?
There is quite an impact on the school summary for Thomas High School. As seen below, the last five values correspond with these categories: Average Math Score, Average Reading Score,	% Passing Math,	% Passing Reading, and	% Overall Passing. Originally, these percentages ranged between 80-90%, after the 9th grade values are changed to NaN, there is a large decrease in these percentages (as seen in the second image)

![This is an image](https://github.com/leilacf/School_District_Analysis/blob/main/original%20school%20summary.png)

![This is an image](https://github.com/leilacf/School_District_Analysis/blob/main/challenge%20school%20summary.png)

  In the second image which reflects the analysis that was done to investigate the potential academic dishonesty, the % Passing Math,	% Passing Reading, and	         % Overall Passing scores decrease to a 60s range. Demonstrating a large discrepancy between both different versions of the data used for analysis.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In comparing Thomas High School's performance relative to other schools when replacing the ninth graders reading and math scores, the analysis did not differ much. As can be seen with both images below, the first one showing the original values and the second one the results after replacing scores with NaN.

![This is an image](https://github.com/leilacf/School_District_Analysis/blob/main/THS%20performance%20original.png)

![This is an image](https://github.com/leilacf/School_District_Analysis/blob/main/THS%20performance%20NAN.png)

- How does replacing the ninth-grade scores affect the following:

  - Math and Reading scores by grade: both the math and reading scores did not differ much from having replaced the ninth-grade scores, the average math scores across all grades at Thomas Highschool originally were 83.6, 83.1, 83.5, and 83.5 After the new analysis with the Nan values in place, they remained in the 83% range. As for average reading scores they were originally 83.7 for 9th grade, 84.3 10th grade, 83.6 for 11th grade, and 83.8 for 12th grade. When the values were changed, the analysis reflected 84.2 for sophmores,	83.5 for juniors, and 83.8 for seniors.
  
  - Scores by school spending: scores by school spending (whether small, medium, or large) were not impacted by the NaN values in the 9th graders data
  - Scores by school size: scores by school size (whether small, medium, or large) were not impacted by the NaN values in the 9th graders data
  - Scores by school type: scores by school type (whether charter or district school) were not impacted by the NaN values in the 9th graders data

## Summary
In conclusion, although most of the changes seen in the analysis after replacing the values with NaN were quite small, there are 4 primary changes to highlight:
1. Average math and reading scores by grade did demonstrate a small decrease in the percentages
2. The school summary was affected drastically, which could serve to highlight the large extent to which the potential academic dishonesty reduced the accuracy of the analysis
3. The district summary changed slightly, although the difference was small, this section of the analysis plays a critical role in the decision making that occurs at the district and state level regarding education funding, opportunities, etc.
4. Lastly, the passing math and reading percentages changed slightly when replacing them for THS without the data on the freshman

