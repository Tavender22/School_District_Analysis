# School_District_Analysis
# Overview:
The purpose of this analysis was to review the testing scores across a range of schools and compare results by type, size, spending and grade. In addition, we needed to remove the grade 9 scores from Thomas High School due to anomalies in both reading and math. 

## Results:
1. District Summary Impact
- Average math scores decreased marginally from 79% to 78.9%.
- Average reading scores were unchanged.
- % passing math, % passing reading and % overall passing all decreased 1%.
Below is a summary of the new district results.
![School District Results](https://github.com/Tavender22/School_District_Analysis/blob/master/Resources/District%20Summary.png)

2. School Summary Impact and How is Thomas High School Impacted
- The only school impacted by the changes made to the data was Thomas High School in terms of results. In terms of raning, Thomas High School drops out of the top 5, replaced by Wright High School.

- Math and reading scores were minimally impacted (less than 1%).
- The % passing math, reading and overall was however significantly negatively impacted, with drops from ~93%, 97% and 90% respectively to  ~67%, 69%, and 65%. This indacates that the grade 9 passing rate was significantly higher than the rest of the school.
![Results by School](https://github.com/Tavender22/School_District_Analysis/blob/master/Resources/School%20Summary.png)

3. Math & Reading Scores By Grade
- Math and Reading scores by grade are not impacted outside of Thomas High School, which shows no result in math or reaing. (i.e. NaN).

4. Scores by school spending
The $630-644 bin sees a significant drop in the % passing math, % passing reading and % passing overall, as a result of the changes caused by Thomas High School.
![Results by School Spending](https://github.com/Tavender22/School_District_Analysis/blob/master/Resources/School%20results%20by%20spending.png)

5. Scores by school size
No material changes occurred in the two analyzes

6. Scores by school type
We see decreases in all charter school % passing categories downward of 4% in math and reading and 3% overall.
![Results by School Type](https://github.com/Tavender22/School_District_Analysis/blob/master/Resources/School%20by%20type.png)

# Summary
With the removal of the Thomas High School results from our dataset we see the following main impacts:
1. Thomas High School drops out of the top 5 school results, replaced by Wright High School.
2. The math passing % drops from ~93% to ~67%.
3. The reading passing % drops from ~97% to ~69%.
4. The overall passing % drops from ~90% to 65%.
5. The scores by school spending see a significant drop in all % passing categories as a result of the change.
6. The charter school passing rates in all % passing categories drops from 3-4%.
