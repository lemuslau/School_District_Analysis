# School_District_Analysis

Project Overview

The purpose of this School District analysis was to arregate dats and schowcase trends for the school board and Superintendent to assist them in their descions for school sudgeting and priorities. In this analysis, the data used was centered around students's standarized test scores and other information about the students' schools to provide a high level insight on several factors of information such as passing percentage, school type, school size, and spending ranges per student.   This analysis was conducted twice, one with the raw data that as given and one altered after is was dicsovered that there could have been potential academic dishonety at one particular school which could skew the information from the first analysis.   

Results

How is the district summary affected?

In comparison between the original data analysis and the updated analysis for district summary was marginal. The "Average Math Score" and "% Overall Passing" fell by 0.1% and the "% passing Math" fell by 0.2%.  Of the test scores the "Average Reading Score" stayed the same but the "% Passing Reading" fell by 0.3%. This was not a dractic drop but it did show the impact academic dishonesty could cause when as a result that schools data is inputted as NaN. 

Initial Analysis <img width="356" alt="Initial Analysis - District_Summary" src="https://user-images.githubusercontent.com/102635884/167349091-bb9b21e9-5337-4849-9ad2-affb5ff6d62e.PNG">
Altered Analysis <img width="393" alt="Altered Analysis - District_Summary" src="https://user-images.githubusercontent.com/102635884/167349080-0d67ab1a-2543-44b9-a43a-ae584fd5d274.PNG">

How is the school summary affected?

The school summary was affected for Thomas High School in several categories. Due to the fact that the ninth graders' math scores were replaced with Nan the following results were seen: 
-The Percentage for "% Passing Math" for the school fell from 93% to 66%, resulting in a category drop of roughly 27%. 
-The Percentage for "% Passing Reading" for the school fell from 97% to 69%, resulting in a category drop of roughly 28%
-The "% Overall Passing" fell from 90% to 65%, resulting in a category drop of roughly 25% 

Initial Analysis <img width="657" alt="School_Summary-Initial" src="https://user-images.githubusercontent.com/102635884/167353788-7fb6a9b9-e6b4-4302-aad5-9232525b6fbb.PNG">

Altered Analysis <img width="638" alt="School_Summary-Altered" src="https://user-images.githubusercontent.com/102635884/167353826-74df2048-b145-4826-8f96-0a0abad6fad1.PNG">

These changes affected Thomas High School on their overall ranking where they went from being on the top list of schools to no longer being on it. 

Initial Top Schools <img width="516" alt="top_schools-initial" src="https://user-images.githubusercontent.com/102635884/167353949-7e6e5b3e-929c-4a37-9b4e-7b20ede7e38c.PNG">

Altered Top Schools <img width="503" alt="top_schools-altered" src="https://user-images.githubusercontent.com/102635884/167353973-15768300-f9a2-48ec-89cf-d4c65c1b12b1.PNG">

The changes from removing that data for the ninth grade scores from Thomas High school resulted in general catgeory scores. 
Scores by school type was affected for Charter Schools where the Percentages for Passing Math and Passing Reading fell by 4% and 3% respectfully. This change brought down the percentage for the entirety of the charter schools which can affect the funding available for the charter schools as a whole.

Intial School Type <img width="364" alt="Initial_School_Type" src="https://user-images.githubusercontent.com/102635884/167355921-ca562eb2-024d-45cc-b127-05d6768a025e.PNG">

Altered School Type <img width="395" alt="Altered_School_Type" src="https://user-images.githubusercontent.com/102635884/167355949-8af6a9b3-dd94-41c3-81d7-6d4ec11fc57c.PNG">


Score by school sized were altered for the school size that Thomas High School landed within. The percentages for Passing Math and Passing Reading fell by 5% for boht catgeories. This shows that a change in one grade for one school was enough to alter that score for school size by a significant amount. 

Initial School Size <img width="380" alt="School_Size_Initial" src="https://user-images.githubusercontent.com/102635884/167355178-50ad767b-962b-49b2-9325-4d8e3aeb1e02.PNG">

Altered School Size <img width="379" alt="School_Size_Altered" src="https://user-images.githubusercontent.com/102635884/167355225-1d13688c-8873-49b3-a335-1785539b7e1f.PNG">

Summary 

Through the 2 different analysis, four changes were apparent which caused a direct affect on the percentages for reading and math score coming from Thomas High School. Replacing the data for the ninth grade students cause a decrease in percentages for these students, the school, and it's affect on school size and school type. Thomas High School dropped from the number two top school to the bottom eighth school. 

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. To view the full script, please open PyCitySchools_Challenge.ipynb in Jupyter Notebook.
