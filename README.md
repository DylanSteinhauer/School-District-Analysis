# School-District-Analysis
## Purpose
I used Pandas and Jupyter Notebook to analyze data on student funding and test taking.
For the challenge, I ommitted Thomas High School's math and reading scores due to potential academic dishonesty.
In addition, I repreated the analysis without Thomas High Schools's scores to see how this affected the analysis.
## Results
### District Summary
![District_Summary_1](https://user-images.githubusercontent.com/87148177/132140832-94c83b8c-bfa0-49fe-a162-858151250456.png)
![District_Summary_Refactored](https://user-images.githubusercontent.com/87148177/132140847-b0813852-ad14-447e-9ccf-370cef9bb3cc.jpg)\
When Thomas High School freshman scores were ommitted, it dropped the overall passing percentage of the district by over 1%.
This was also true for the passing math and passing reading percentages for the district.
### School Summary
![School_Summary_1](https://user-images.githubusercontent.com/87148177/132141011-ffa7460d-b2df-4ef7-919f-4e10cb47224f.png)
![School_Summary_Refactored](https://user-images.githubusercontent.com/87148177/132141013-0106f926-1172-4453-900a-29b106ec16ae.jpg)\
When looking at the school summary, we see that Thomas High School's passing percentage went from over 90% to about 65% after the freshman were omitted.
Their passing reading percentage also dropped by almost 30%.
Similarly, their passing math percentage dropped by about 27%.
### Thomas High School Comparative Analysis
After the initial analysis, Thomas High School had the second highest passing rate in the whole district with 90.95%.
After their passing rate dropped to 65%, they became the 7th highest passing rate in the district out of 15 schools.
### Math and Reading Scores by Grade
![Math_Scores_by_Grade](https://user-images.githubusercontent.com/87148177/132141494-cfe6b447-742b-4ffe-a659-19a66223bba5.png)
![Reading_Scores_by_Grade](https://user-images.githubusercontent.com/87148177/132141497-089e870c-dd70-4f93-9885-e4ce74c38f5d.png)\
When looking at the math and reading scores by grade, the data is unaffected because the 9th grade scores from Thomas High School are displayed as NANs.
### Scores by School Spending
![Spending_Summary_1](https://user-images.githubusercontent.com/87148177/132141687-09c89d22-1c22-40a4-9750-b76bae9dd86c.png)
![Spending_Summary_Refactored](https://user-images.githubusercontent.com/87148177/132141692-9c6a9594-9c53-4c2e-a66a-186d986cd2a9.png)\
This change in data affected the spending ranges for passing percentages. 
According to the summary, there was a 6% decrease in percentage passing math, a 7% decrease in passing reading percentage, and a 6% decrease in overall passing percentage in the $630-644 spending range.
### Scores by School Size
![Size_Summary_1](https://user-images.githubusercontent.com/87148177/132141793-70ba68cf-50cf-4034-9b65-0b6bce80f67b.png)
![Size_Summary_Refactored](https://user-images.githubusercontent.com/87148177/132141796-a36c2b59-41e6-4db3-bf0f-d4f76652d069.png)\
Medium sized schools had their passing percentage changed by 6%, dropping from 91% to 85%. The other two school sizes were unaffected.
Similarly, the passing reading and passing math percentages both dropped by 6% for medium schools.
### Scores by School Type
![School_Type_1](https://user-images.githubusercontent.com/87148177/132142223-9eb0696b-5ea7-4187-8173-95f898f3aa92.png)
![School_Type_Refactored](https://user-images.githubusercontent.com/87148177/132141925-4f3d7231-fe2c-4f7b-8d9a-31e7c2deae81.png)\
The overall charter passing percentage dropped from 90% to 87% after the analysis was performed again.
The passing reading and math percentage for charter schools both dropped by 4 percentage points.
## Summary
After the analysis was re-ran, the new data greatly harmed the passing percentage for Thomas High School.
It went from one of the best performing schools to middle of the pack. The omission of Thomas freshmen also noticably affected schools within
the $630-644 spending range per student. A 6% change in passing percentage is a noticable change. 
The change was also noticable when looking at schools types, with a 3% decrease.
