# School District Analysis

## Overview of the school district analysis

Since we helped Maria with the analysis of the school district, the board saw some discrepancies and/or dishonesty with certain data entries. They notified Maria of this and wanted to get it all sorted out. She in turn, requested help to modify the code to add any nulls. We want to see how the district performed with the data. As you read further on, you will see the difference.

## Results

* How is the district summary affected?
* * If we look at the modified and original summaries, you will see that the modified summary **(output line[16])** has lower percentages than that of the original **(output line[90])**. They may be subtle, but, a smart fraction of percentage can sometimes make a big impact
* * ![Combined District](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined-District-Summaries.png?raw=true)
* How is the school summary affected?
* * If we look at the modified and original summaries, you will see that the modified summary **(top part of the image)** is significantly higher than the original. **(bottom part of the image)** We have to take into account that part of the code was removed to accomdate the adjustment. We essentially removed the freshman (ninth graders) scores and added nulls.
* * ![Combined Thomas](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined-School-Summaries.png?raw=true)
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* * As stated above, adding the null scores (ninth graders) increased the performance of Thomas High School dramatically.
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
* * * When we look at the percentage of scores via the medium school size, you will notice the modified code **(top part of the image)** will higher percentages than the original **(bottom part of the image)**. Even though these percentages are less than one percent of a difference, when the code is formatted and the numbers are rounded. You will barely see a difference in the results.
* * * ![Combined-Size](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined%20School%20Size.png?raw=true)
* * Scores by school type
* * * When we look at the percentage of scores via the type of school being charter, you will notice that the modified code **(top part of the image)** will be lower than the original **(bottom part of the image)**
* * * ![Combined-Type](https://github.com/Greekman12490/School_District_Analysis/blob/main/Image%20Resources/Combined%20School%20Type.png?raw=true)

## Summary

When we compare both the original and modified versions of the code. You will notice some subtle changes with the percentages. When the ninth graders were replaced with NaNs, you will notice changes scores by school size, type and grade levels. The score percentages will not have a percentage change above or below 1%. Some of which will not show much of a difference if the percentages were formatted and rounded up to the nearest tenth of percent. The biggest change that we saw was when it came to Thomas High School summary. As the scores became significantly higher.

