# PyBer with Matplotlib

## Overview of the PyBer Analysis
In order to make appropriate business decisions, information captured from ride and city data should be presented in summary dataframe form and line graph form.  In doing so, company leadership will be able to make decisions based on most profitable city types, fare trends by city type over several weeks, average fares per ride by city type, and average fares per driver by city type.

## Pyber Ride & City Analysis Results
Some results are to be expected:  for example, across all displayed metrics, rural areas have the smallest number of total fares, rides, and drivers, with suburban and urban being larger and largest, respectively.  However, interestingly, average fare per ride and per driver are highest in rural areas and lowest in urban areas with suburban remaining between the two.
* Total Fares by City Type 
* ![TFBCT](analysis/PyBer_fare_summary.PNG)
* ![PSDF](analysis/pyber_summary_df.PNG)

***

* School Summary Impact
  * Before Removing THS 9th Grade Scores:  ![Old_School_Summary](Resources/school_summary_old.PNG)
  * After Removing THS 9th Grade Scores:  ![New_School_Summary](Resources/school_summary_new.PNG)
  * Of course, removing the dishonest THS 9th grade scores from the data did not have an impact on any high school but THS.  Removing these scores had an impact on the THS averages and passing rates.  Average math scores decreased by .07%, average reading scores increased by .05%, percent of students passing math decreased by .09, percent passing math in THS dcecreased by .29%, and overall passing students decreased by .32%.  Again, removing the scores did not appear to have a significant impact on average school scores and average passing rate at THS.

***

* Impact on THS Performance (Relative to Other Schools)
  * Top 5 Schools Before Removing THS 9th Grade Scores:  ![Old_Top_Five](Resources/old_top_five.PNG)
  * Top 5 After Removing THS 9th Grade Scores:  ![New_Top_Five](Resources/new_top_five.PNG)
  * Relative to the other schools, while the values for THS overall did change, the changes were not significant enough for THS to lose its standing as the #2 school in the disctict.

***

* Additional Impact Analysis:
  * Math Scores (Before Removing THS 9th Grade Scores):  
  ![Old_Math_Scores](Resources/math_scores_by_grade_old.PNG)
  * Math Scores (After Removing THS 9th Grade Scores):  
  ![New_Math_Scores](Resources/math_scores_by_grade_new.PNG)
  * Reading Scores (Before Removing THS 9th Grade Scores):  
  ![Old_Reading_Scores](Resources/reading_scores_by_grade_old.PNG)
  * Reading Scores (After Removing THS 9th Grade Scores):  
  ![New_Reading_Scores](Resources/reading_scores_by_grade_new.PNG)
  * With the obvious exception of having NaN values for the 9th grade scores, removing the scores had no impact on the analysis; other schools and grades' average scores remained the same.

***

   * Scores by school spending
     * ![Spending_Old](Resources/spending_old.PNG)
     * ![Spending_New](Resources/spending_new.PNG)
     * There was no significant impact (may be measurable in tenths or hundredths of a percent).

***

   * Scores by school size
     * ![Size_Old](Resources/size_old.PNG)
     * ![Size_New](Resources/size_new.PNG)
     * There was no significant impact (may be measurable in tenths or hundredths of a percent).

***

  * Scores by school type
    * ![Type_Old](Resources/type_old.PNG)
    * ![Type_New](Resources/type_new.PNG)
    * There was no significant impact (may be measurable in tenths or hundredths of a percent).

## School District Analysis Summary
Upon removal of the dishonest 9th grade scores from THS, there was minimal impact on many metrics by school and for the entire district.  Due to the size of THS' 9th grade class (less than 10% of the total population) and the fact that scores didn't vary greatly from the rest of the school's scores, are both factors contributing to the relatively unchanged results and analysis.

Across all analyzed metrics, increased spending, smaller school sizes, and charter schools tend to achieve more successful results.  Spending, the type of school, and school size seem to be far more important for achieving better passing rates and test scores, though there appears to be diminishing returns in some cases with the smallest schools and the highest per capita spending.  The dishonest 9th graders did not have a significantly negative impact on their school standing in the district.

Another analysis of the data, this time replacing all 9th grade THS scores with "0", would likely show a much more realistic and profound impact of the academic dishonesty.
