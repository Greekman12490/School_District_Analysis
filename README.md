# School District Analysis

## Overview of the school district analysis

Since we helped Maria with the analysis of the school district, the board saw some discrepancies and/or dishonesty with certain data entries. They requested Maria of this and wanted to get to the bottom of this. She in turn, requested help to modify the code to remove any nulls and see how the district performed with the removed data. As you read further on, you will see the difference.

## Results

* How is the district summary affected?
* * If we look at the modified and original summaries, you will see that the modified summary **(output line[16])** has lower percentages than that of the original **(output line[90]). They may be subtle, but, a smart fraction of percentage can sometimes make a big impact
* * ![Combined District](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined-District-Summaries.png?raw=true)
* How is the school summary affected?
* * If we look at the modified and original summaries, you will see that the modified summary **(top part of the image)** is significantly higher than the original. **(bottom part of the image)** We have to take into account that part of the code was removed to accomdate the adjustment. We essentially removed the freshman (ninth graders) null scores. 
* * ![Combined Thomas](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined-School-Summaries.png?raw=true)
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* * As stated above, removing the null scores (ninth graders) increased the performance of Thomas High School dramatically.
* How does replacing the ninth-grade scores affect the following:
* * Math and reading scores by grade
* * * When you look at the images below, the only difference you will see is that the freshman (ninth graders) scores will have a null value taking it's place within the modified code **(top image)** and the original will have a numerical value. **(bottom image)**
* * * ![Combined-Mod-Score](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined%20Modifed%20Scores.png?raw=true)
* * * ![Combined-Ori-Score](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined%20Orignal%20Scores.png?raw=true)
* * Scores by school spending
* * * The images below will show that the original scores **(bottom image)** will be higher than the modified scores **(top image)** based on school spending.
* * * ![Mod-Spending](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Modified%20Spending.png)
* * * ![Ori-Spending](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Original%20Spending.png)
* * Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
