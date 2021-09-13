# School_District_Analysis
## Overview of the School District Analysis
Following proof of academic dishonesty concerning the reading and math grades for Thomas High School ninth graders, the school board has commissioned this project in order to adjust, reassess, and reanalyze scores of the schools in the district. The analyses required me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Then, I repeated the school district analysis that I did in this module.

### Purpose of Analysis
The main purpose of this project was to find out whether the changes in grade scores affected the overall analysis.

### Resources
Software used: Anaconda, Jupyter Notebook, Pandas, and Python
Databases: school_complete_data.csv, student_complete_data.csv, PyCitySchools.ipynb

## Results
Once the scores of the ninth graders from Thomas High School were removed, the result for Thomas High School yielded a very small difference. With regard to the percentage for overall passing, the value obtained in the module was 90.948012, while the final result showed a slight decrease: 90.630324. We can also note that while there was a small decrease in the percentage of overall passing grades for Charter schools (from 90.432244 to 90.392533), the value has remained unchanged for District schools (53.672208). Thus, we can expect similarly slight differences for other variables. Other small changes for students at Thomas High School are:

* the average math_score decreased slightly from 83.418349 to 83.350937 
* the average reading_score increased slightly from 83.848930 to 83.896082 
* the percentage for passing math decreased from 93.272171 to 93.185690 
* the percentage for passing reading decreased from 97.308869 to 97.018739 

### Metrics
* a slight increase in reading scores for Medium-sized schools (1,000-2,000 students)
* a small decrease in the percentage of overall passing grades for Charter schools, but no change for District schools
* no changes in the per-student school spending metric
* all math and reading scores for ninth grade students from Thomas High School are listed as NaN, but by-grade scores have not changed oterhwise

## Summary
As the images below show, the top five schools based on overall passing percentage are: Cabrera High School, Thomas High School, Griffin High School, Wilson High School, and Pena High School.

![Screen Shot 2021-09-13 at 3.58.24 AM.png](https://github.com/Irina-Preotescu/School_District_Analysis/blob/1f82e2a5522b19138860aa2f2c84128c271138fe/Screen%20Shot%202021-09-13%20at%203.58.24%20AM.png)


The five lowest scoring schools on the same metric are: Johnson High School, Hernandez High School, Huang High School, Figueroa High School, and Rodriguez High School.

![Screen Shot 2021-09-13 at 3.58.55 AM.png](https://github.com/Irina-Preotescu/School_District_Analysis/blob/b302c5c62cf5383ea699b4fc00241783b3777b7e/Screen%20Shot%202021-09-13%20at%203.58.55%20AM.png)

## Conclusion
As a result of the analysis, the changes recorded after reading and math scores have been replaced are minimal and do not suggest a significant difference in the overall analysis process. However, four slight changes are visible:
1. a decrease in the overall passing grade percentage for students at Thomas High School
2. a decrease in overall passing grade percentage for students in Charter schools
3. a decrease in the average math score for students at Thomas High School
4. an increase in the average reading score for students at Thomas High School
