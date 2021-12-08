# STEM-courses-Salary

The original dataset has 62642 rows and 29 columns

After removing null values in the Educations, there are 30370 rows remaining that we can work with. Since our primary question deals with the Education level, it was important to not have null values in the column to make conclusions from our analysis.

The dataset has the following columns:
'timestamp', 'company', 'level', 'title', 'totalyearlycompensation',
       'location', 'yearsofexperience', 'yearsatcompany', 'tag', 'basesalary',
       'stockgrantvalue', 'bonus', 'gender', 'otherdetails', 'cityid', 'dmaid',
       'rowNumber', 'Masters_Degree', 'Bachelors_Degree', 'Doctorate_Degree',
       'Highschool', 'Some_College', 'Race_Asian', 'Race_White',
       'Race_Two_Or_More', 'Race_Black', 'Race_Hispanic', 'Race', 'Education'
       
       <img width="491" alt="image" src="https://user-images.githubusercontent.com/25436991/145306295-f7fb65dc-8588-471f-90f7-f9f7333f739d.png">

#### Count of employees by education level

<img width="271" alt="image" src="https://user-images.githubusercontent.com/25436991/145306342-fc64e8d5-6ce5-40d7-af58-abcc265a9880.png">


<img width="655" alt="image" src="https://user-images.githubusercontent.com/25436991/145306370-83792c3c-de7f-4a5f-8dca-aeb49df7fe11.png">

From the above graph, we can see that more than 15000 (50%) employees in this dataset hold a Master's degree.


#### Average Total Yearly Compensation by Education

<img width="348" alt="image" src="https://user-images.githubusercontent.com/25436991/145306448-ff5770e9-511c-46a7-bcb3-924b375e8225.png">


#### Box plots of total yearly compensation by education level

<img width="690" alt="image" src="https://user-images.githubusercontent.com/25436991/145306483-8673acd6-1b63-46a1-88b9-18da0e357995.png">

#### Total Yearly Compensation by Top tech companies

<img width="553" alt="image" src="https://user-images.githubusercontent.com/25436991/145306521-482feea7-57ed-4987-a5e5-987567d3b2bc.png">


<img width="861" alt="image" src="https://user-images.githubusercontent.com/25436991/145306550-5b158c88-7808-47a5-bbac-65c93b51b1a8.png">


#### Average Total Yearly Compensation by Experience Level

<img width="353" alt="image" src="https://user-images.githubusercontent.com/25436991/145306588-26ba5167-d878-4e5d-b8b8-2a7d2c5975a2.png">


#### Boxplot of Total Yearly Compensation by Education and Experience Level

<img width="767" alt="image" src="https://user-images.githubusercontent.com/25436991/145306618-af65382d-96f4-4d98-9642-292ac57d6bca.png">



**Further analyzing job locations within the US**

<img width="573" alt="image" src="https://user-images.githubusercontent.com/25436991/145306654-7ab531cc-d639-40c7-8fce-30f11c397306.png">

<img width="1286" alt="image" src="https://user-images.githubusercontent.com/25436991/145306679-21375f30-912e-44be-82cb-35636a540ccb.png">


#### Analyzing Gender

<img width="552" alt="image" src="https://user-images.githubusercontent.com/25436991/145306729-0328e6ec-07d5-47f6-a07d-a7b2fc3a36b9.png">


**Looking specifically at Business Analysts and Data Scientists**

<img width="732" alt="image" src="https://user-images.githubusercontent.com/25436991/145306767-72084123-8eab-4550-be85-b176a02785c7.png">


## Hypothesis Testing

<img width="578" alt="image" src="https://user-images.githubusercontent.com/25436991/145306828-d8e57283-0140-4fee-b408-6fa5321ccef4.png">

Applying a logarithmic distribution to fix the issue.

<img width="608" alt="image" src="https://user-images.githubusercontent.com/25436991/145306857-72a00c91-5135-4f97-8661-c09de4724e86.png">


<img width="552" alt="image" src="https://user-images.githubusercontent.com/25436991/145306904-fbe2bfa5-fcbc-4026-b9ca-209f38c648ef.png">

**The p-value is much smaller than any alpha level we decide to choose. At the 99% level, we can reject the null hypothesis. We can conclude that the salary of a person who holds a Masters degree is greater than the salary of a person who does not have a Masters degree (excluding PhD)**


## Linear Regression Analysis

<img width="630" alt="image" src="https://user-images.githubusercontent.com/25436991/145306949-cbb65d80-ad15-4110-a59f-39b2a6906d71.png">


### Does a master's degree have an impact on total yearly compensation, controlling for gender? 

<img width="643" alt="image" src="https://user-images.githubusercontent.com/25436991/145306977-15efe49a-77e6-4f58-847b-7a0ccdd62961.png">


### Does having a master's degree lead to a higher total compensation for data scientists/business analysts?

<img width="782" alt="image" src="https://user-images.githubusercontent.com/25436991/145307040-127aa6c5-8e95-4ed8-a0b2-b7d1111e0509.png">

#For Non Data Science & Business Analytics Roles
<img width="766" alt="image" src="https://user-images.githubusercontent.com/25436991/145307065-37ac736e-6ba8-4704-acdd-5743ebe8a826.png">


<img width="765" alt="image" src="https://user-images.githubusercontent.com/25436991/145307170-88c338f4-ecd5-46f5-bc04-3221c0483bf9.png">

<img width="621" alt="image" src="https://user-images.githubusercontent.com/25436991/145307198-7e608c1e-da5f-448e-9c9f-ef3194b1730f.png">













