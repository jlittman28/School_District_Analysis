# School_District_Analysis

## Overview
Acaedemic integrity is pivotal in fostering a creative and collaborative environment within the academic community. Maria (the client) informed us that the school board notified  their firm of academic dishonesty among ninth graders at Thomas High School (THS). We were tasked with replacing ninth grader's scores with NaN at Thomas High School, while leaving all other school data untouched.   

## Results

* How is the district summary affected?
   * The new student count decreased by 461 from 39,170 to 38709   
    
    ![image](https://user-images.githubusercontent.com/85204128/125150200-14d08880-e10c-11eb-89d6-30bb2f953db1.png)

* How is the school summary affected?
  *  
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  Using loc method to replace math/reading scores, the performance went up. Previously in the bottom 5 schools, overall % passing for Thomas High School increased
  
  ### THS Scores including ninth graders
  
  ![image](https://user-images.githubusercontent.com/85204128/125150091-1057a000-e10b-11eb-8b82-6e878a78f12c.png)

  ### THS Score excluding ninth graders
  
  ![image](https://user-images.githubusercontent.com/85204128/125150109-27968d80-e10b-11eb-8efe-195a168d3bd8.png)

* How does replacing the ninth-grade scores affect the following:
  * ### Math and reading scores by grade
    * Increased the math/reading score passing % for THS  
  * ### Scores by school spending
    * The scores went down slightly when removing Ninth Graders from the analysis, however, when rounded the scores were unchanged.
  * ### Scores by school size
    * The scores went down slightly when removing Ninth Graders from the analysis, however, when rounded the scores were unchanged.
  * ### Scores by school type
     * The scores went down slightly when removing Ninth Graders from the analysis, however, when rounded the scores were unchanged.
      
    
     * ### Including Ninth Graders
     ![image](https://user-images.githubusercontent.com/85204128/125149609-fa94ab80-e107-11eb-904f-d55b56fa4462.png)
      
     
     * ### Excluding Ninth Graders
     ![image](https://user-images.githubusercontent.com/85204128/125149605-f10b4380-e107-11eb-9b47-9c79c14ce496.png)


## Summary

  1. Total THS Student Count decreased
  2. % Passing Math increased due to lower student count base by school (THS)
  3. % Passing Reading increased due to lower student count base by school (THS)
  4. % Overall Passed increased due to lower student count base by school (THS)
