![image](https://github.com/AzadMehedi/Projects/assets/49702660/d5c750d3-0912-4b45-b0f4-891de1ddef11)

<h1>Project Title: EDA & Prediction of Data Domain job Salaries</h1>

<h1>Programming Language used: <col='red'>Python</col></h1>

<h1>Environment: kaggle Notebook & Google Colab</h1>

<h1>Machine Learning Library used: Scikit Learn</h1>

<h1>Used Machine Learning Models:</h1>

<ol>
  <li>Random Forest</li>
  <li>GradientBoosting</li>
  <li>XGB</li>
  <li>ExtraTree</li>
  <li>DecisionTree</li>
  <li>LGBM</li>
  <li>KNeighbors</li>
</ol>

<h1>Best Accuracy: 0.948997	</h1>
<h1>Random Forest</h1>

<h1>Data Manipulation Tools used::</h1>
<ol>
  <li>Pandas</li>
  <li>Numpy</li>
</ol>

<h1>Visualization Tools used::</h1>
<ol>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>plotly</li>
</ol>

<h1>This project is about Exploratory Data Analysis and Predictions on Salaries of Data Domain field.</h1>

Explaining the dataset

<h2>work_year: The year the salary was paid.</h2>

<h2>experience_level: The experience level in the job during the year with the following possible values</h2>
<li>EN : Entry-level</li>
<li>MI : Junior Mid-level</li>
<li>SE : Intermediate Senior-level</li>
<li>EX Expert Executive-level / Director</li>

<h2>employment_type: The type of employment for the role</h2>
<li>PT : Part-time</li>
<li>FT : Full-time</li>
<li>CT : Contract</li>
<li>FL : Freelance</li>

<h2>job_title: The role worked in during the year.</h2>
<h2>salary: The total gross salary amount paid.</h2>
<h2>salary_currency: The currency of the salary paid as an ISO 4217 currency code.</h2>
<h2>salary_in_usd: The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com.</h2>
<h2>employee_residence: Employee's primary country of residence in during the work year as an ISO 3166 country code.</h2>

<h2>remote_ratio: The overall amount of work done remotely, possible values are as follows</h2>
<li>0 : No remote work (less than 20%)</li>
<li>50 : Partially remote or Hybrid</li>
<li>100 : Fully remote (more than 80%)</li>

<h2>company_location: The country of the employer's main office or contracting branch as an ISO 3166 country code.</h2>

<h2>company_size: The average number of people that worked for the company during the year</h2>
<li>S : less than 50 employees (small)</li>
<li>M : 50 to 250 employees (medium)</li>
<li>L : more than 250 employees (large)</li>

<h1>Exploratory Data Analysis</h1>

<h2>Let's See Univariate Analysis</h2>
<ol>
  <h2>Distribution of salary</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/436d29af-60c2-4e3e-bc08-6206ee907fc9)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/1e661336-2ae7-429e-8e65-eda6cdba09ef)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/20338e1f-839f-4709-81e0-df749ff2acb1)



  <h2>experience_lavel</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/1bd26e73-60d3-44ad-8a2d-61ace0794222)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/235ad17f-360d-47cd-bcc8-34b43a6bfce7)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/71a25919-0a18-493a-b7b1-531560fd5886)
  
  <h3>Observation:</h3                 
  <h4>We can see from the above pie chart that senior level jobs mostly requires experience.</h4>

  <h2>employment_type</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/f15e83f4-7669-4543-942a-06457d958bcb)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/db5dc549-f13f-450f-8cbd-58d4c4840766)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/d81d74bd-4b04-4ac0-81aa-9a0a5670b41d)
  
  <h3>Observation:</h3>
  <h4>
    <ol>We can see that 96.9% of the jobs are Full-time jobs.</ol>
    <ol>Contract and freelancing jobs are not given that much importance in Data Science.</ol>
    <ol>Part Time jobs are also rare.</ol>
  </h4>



  <h2>job_title</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/81a240d6-5ef3-4aa4-bc9c-c43fadc3d921)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/bc781f44-dd72-4dac-bf5f-e802b4176dc4)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/6517e334-3c92-433b-a57e-158b3f9f639c)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/0896f99a-b8c7-4387-9d7d-8211b9d77592)
  
  <h2>Observations:</h2>
  <ol>After Centralize we got 10 main job category.</ol>
  <ol>Data Scientist;s Average Salary gain top position.</ol>
  <ol>Machine learning Engneer's Salary got Second Position.</ol>

  <h2>Employee Residence and Company location</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/8c992af9-be90-4aaa-8579-ce2935723760)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/f5324911-ad1e-4336-a551-9fa42b0efe4f)
  
  <h3>Observations:</h3>
  <ol>Maximum Data Domain Jobs seen in the USA.</ol>
  <ol>Then UK, Canada, Germany, India, France so on</ol>

  <h2>Remote ratio</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/398825d6-128c-410d-8eb9-988bfd5ab0e2)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/66159f3c-802d-4646-9437-73102b0b2bdb)
  
  <h3>Observations:</h3>
  <ol>Fully Remote job type ratio is way more than other types.</ol>
  <ol>Then On-Site job type</ol>
  <ol>Lastly, Partially or Hybrid job type.</ol>

  
  <h2>Let's See Bivariate Analysis</h2>
  
  <h2>Work Year and Remote Ratio</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/4f0798bd-39d3-4570-bd4b-c75ad96ea627)

  
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/567cc965-e49e-4d25-9fe1-79cacfddb959)

  <h3>Observations:</h3>
  <ol>Fully Remote ratio Increased each year.</ol>
  <ol>Partially or Hybrid ratio Increased in 2021 year but decreased 2020.</ol>
  <ol>On Site ratio decreased each year.</ol>


  <h2>Relationship between salary and work year</h2>
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/e2eda158-f0e0-4b35-b819-78910ca43813)
  
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/7445d517-2345-4b5e-891f-de6e315d146b)

  <h3>Observations:</h3>
  <ol>Average salaries increased each year.</ol>
  


  <h2>Relationship between Salary and company size</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/0eae179a-152c-4a34-bf37-50e3788a57cf)

  <h3>Observations:</h3>
  <ol>comparetively Larger comapany pays more salary.</ol>

  <h2>Job Types and Experience Level distributions</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/e0f1a243-f892-44bc-83e5-ec7bddc5c098)

  <h3>Observations:</h3>
  <ol>Fully Remote job has the highest number of job opening.</ol>
  <ol>Senior level job has the highest number of job opening.</ol>

  <h2>relationship between Salary and employment_type</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/6558e706-921b-4630-8eda-76ec07ba3b90)

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/18810dbc-e148-40a9-82a4-b773bad8c0a0)

  <h3>Observations:</h3>
  <ol>Contract based employee get higher amaunt Average salay. Then Full time based employee. Then Freelance and part time based employee.</ol>
  <ol>Some full time based employee gets higher amount than others.</ol>


  <h2>Top 10 Roles in Data Science based on Average Pay</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/e7e32a6d-a4a6-48f6-9692-5fe8d22c4f5e)

  <h3>Observations:</h3>
  <ol>Average Salary of Data Architech is Higher than others.</ol>

  <h2>top 10 popular Data science role</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/4016e49c-e2c8-4c18-9fdc-a9ddf1f16ad4)

  <h3>Observations:</h3>
  <ol>There are more jobs in Data Science Field.</ol>
  <ol>Then Data Engineer and Data Analyst</ol>
  
  <h2>Top 10 roles in Data Science role according to salary</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/bda16157-7153-487b-8f31-deedac7f6f2a)

  <h3>Observations:</h3>
  <ol>According to Salary, Data Engineer earn more than others.</ol>
  <ol>Data Analyst, Research Scientist, Machine learning Engineer and Data Scientist earn almost same.</ol>


  <h2>Job title and Experience level</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/aaec7864-4a1b-4177-9c4e-4c4b2014d0d3)

  


  <h2>Relationship of Job Title and Salary</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/82fc959c-c560-4aba-ab0a-2e2c29d31f33)

  <h3>Observations:</h3>
  <ol>Senior Employee is more in Almost every Job role.</ol>

  <h2>Job title and Employment Type</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/e2dbb93c-6a81-4eb4-8d14-742d6495585b)

  <h3>Observations:</h3>
  <ol>Count of Fully Remote is in Top position in most job title.</ol>

  <h2>Company Size VS Job Type Counts</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/41a20227-826d-4f6b-85da-a85d5c25e0f1)

  <h3>Observations:</h3>
  <ol>Small-sized companies provide minimum onsite opportunities,</ol>
  <ol>whereas Medium-sized companies provide maximum remote work opportunities.</ol>

  <h2>Relationship between Salary and Exprience</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/d88e433f-290c-4291-a13d-376273051abe)

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/2f41e666-351f-4fdc-a0d5-56b7f4764d19)

  <h3>Observations:</h3>
  <ol>According to Experience level, Mean & Maximum Salary of Executive levels got first position.</ol>
  <ol>'Senior Level' in Mean salary section got second position.</ol>
  <ol>'Middle Level' in Maximum salary section got second position.</ol>


  <h2>Multivariate Analysis</h2>
  
  <h2>Corelation between Features</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/719e9757-c446-4288-a306-07e41ae0726b)

  <h3>Observations:</h3>
  <ol>The Highest correlation of salary is with:</ol>
    <ol>1. Employee Residence</ol>
    <ol>2. Company Location</ol>
    <ol>3. Experience Level</ol>
    <ol>Employment type & Company size has a Negative correlation</ol>
 

  <h2>job type and company size VS salary</h2>
  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/3d1794de-765f-4cb0-a113-5d9331a4b440)

  <h3>Observations:</h3>
  <ol>Lowest salary is seen in onsite job for a small company.</ol>
  <ol>Higher salary is seen in Fully remote job for a laege company.</ol>

  
  <h2>The relationship between salary_in_usd and experience_level and work_year</h2>

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/129be106-07ca-4d88-ad20-17bf3c85b20b)

  ![image](https://github.com/AzadMehedi/Projects/assets/49702660/380d025c-792d-491d-b166-f2469d6fb3e8)


</ol>

<h1>Model Accuracy</h1>

![image](https://github.com/AzadMehedi/Projects/assets/49702660/680b428a-115d-4a82-8842-493a8b001158)






