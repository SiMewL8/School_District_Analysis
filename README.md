# School_District_Analysis
Helping analyze school testing results


## Challenge

After sifting through the school and student’s data, we decided to omit the math and reading scores for 9th graders in Thomas High School since there was a data integrity issue. After replacing the data with NaN (not a number) values, here we must compare the results from the original summaries to the new adjusted summaries. First let’s start with District Summaries. 

### District Summary

**Original**

![distold](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/dist_summ_old.PNG?raw=true)


**Fixed**

![distnew](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/dist_summ_new.PNG?raw=true)

Here we can see the changed values:

1. Average Math Score dropped by 0.1 points.
2. The passing percentages for Reading, Math, and Overall dropped by 1%.

The changes show a 1% drop in the passing percentages. The average math scores in the whole district dropped by .1 points, while the average reading score stayed the same.

### School Summary

**Original**

![pskolold](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/perschool_summary_old.PNG?raw=true)

**Fixed**

![pskolnew](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/perschool_summary_new.PNG?raw=true)

The changed values should only be reflected onto Thomas High School since this is a summary of all the schools. The changes are:

1. Average Math Score stayed the same. However, the Average Reading Score elevated by .1 points.
2. The Passing percentages had significant drops, 26% drop for Math, 27% drop for Reading. 
3. The Overall percentages had 26% drop.

The unchanging averages show that, most likely, each of the grade levels had about the same averages for math and reading scores in Thomas High School. However, replacing the data for 9th graders amounted to significant percentage drops in students passing Math, Reading, and Both scores (about 30% drop!). This change was to be expected. 

### Top Overall Percentages

**Original**

![topold](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/bottom_school_old.PNG?raw=true)

**Fixed**

i![topnew](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/bottom_school_new.PNG?raw=true)

After changing the data, Thomas High School dropped from the top spot of 91%, which was tied with 4 other schools, to 65%. It has dropped to the middle of the pack.  


### Average Scores per School

**Original**

![avgold](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/avg_math_read_old.PNG?raw=true)

**Fixed**

![avgnew](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/avg_math_read_new.PNG?raw=true)

There isn't much to compare as we can see the math and reading scores for 9th graders at Thomas High School were replaced with NaNs values, thus the scores were dropped completely.

### Scores by School Spending

**Original**

![spndold](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/spedning_summay_old.PNG?raw=true)

**Fixed**

![spndnew](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/spedning_summay_new.PNG?raw=true)

Few things to note:

1. The Averages of all both Math and Reading Scores stayed the same.
2. For the $630-644 per student Spending Range, the Passing percentages changed significantly. Math passing went down by 6%, Reading passing went down by 7%, and the Overall passing went down by 7% as well.

Only the passing percentages in the $630-644 spending category had a slight drop. We know this because Thomas High School falls under that School Spending Range. All other values stayed the same. 

### Score by School Size

**Original**

![dbubfu3ghgg](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

**Fixed**

![dbubfu3ghgg](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

Here are the changes:

1. The Averages scores stay the same.
2. The Passing percentages for the Medium Size range have dropped. Math, Reading, and Overall percentages all dropped by 6%.

It is expected that the averages should mostly stay the same. The significant change is brought in the Passing percentages again, and it becomes apparent as Thomas High School falls under the Medium School Size.

### Score by School Type

**Original**

![typeold](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/type_school_old.PNG?raw=true)

**Fixed**

efegrgqhebvrhr.png

![typenew](https://github.com/SiMewL8/School_District_Analysis/blob/master/summaries_pngs/type_school_new.PNG?raw=true)

1. Values aren't affected in the District category.
2. Charter category had the same percentages compared to the original, but the newfound pattern of passing percentage drops has been repeated here as well. Both Math and Reading shared a 4% drop, while Overall had a 3% drop.

We know for a fact that Thomas High School is a Charter School. So, the scores and percentages were only affected in the Charter category. As is the pattern, Averages scores stayed the same, but the Passing percentages had slight drops.


















