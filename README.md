# Data Scientist & Data Analyst

#### Summary

Current data analyst with 4 years of experience, seeking an analyst role with expertise in data collection, analysis, and reporting. Additional **focus on verbal and written communication skills** with a track record of working in collaborative team environments. Increased annual revenue of a record distribution company by 8% in 2023 by collaborating with the product management team and performing cohort analysis. Skilled in **data validation, handling inquiries, creating scheduled/ad hoc reports, and data visualization**. A proven track record in enhancing data infrastructure and providing reports to stakeholders.

#### Technical Skills: Python, SQL, AWS, R, MATLAB, Azure, Power Bi, Excel, CSS, HTML, Git

## Education

- Bachelors of Science, Data Science | The University of North Carolina at Charlotte (_May 2024_) 3.6/4.0 GPA
- Associates, Computer Science | Central Piedmont University (_May 2022_) 3.5/4.0 GPA

### Work Experience
**Data Analyst – 33 1/3 Record Distribution (_May 2020 - April 2024_)**
- Analyze extensive customer sales data to develop insightful **PowerBI dashboards and visualizations**.
- Collaborated with the product management team to perform **cohort analysis**, leading to pricing strategies that **increased annual revenue by 8%** in 2023.
- Created structured **SQL** databases (MySQL) for **data storage, management, and inquiries, documenting processes, SQL queries**, and stored procedures.
- Leveraged excel functions, including **VLOOKUPs, XLOOKUPs and pivot tables**, to simplify analysis and reporting processes.

## Projects
### 1. Policing with Predictive Modeling
[Link](https://github.com/Hippobot/Policing-with-Predictive-Modeling/tree/main)

In 2022, the Charlotte Mecklenburg Police Department gave out a complex data set spanning multiple years which detailed all sorts of crimes, locations, and many other criteria. The dataset was non anonymized while also having close to 1 million rows and 100s of features (columns). The dataset was not clean and lacking any rubric/legend to reference for the column labels. I was tasked to see if I can bring any insights to the table from this dataset and present to the relevant stakeholders. I led a team of 4 of my peers to publish a report on the CMPD data and construct an **XG-Boost classification model** to predict vehicle crime from car characteristics (model, make, color, etc). **ArcGIS** was used to spatially join the shape files to the csv police dataset and create distance buffer zones. Excel was used to **clean and organize the data**, then used python to initialize everything. This **resulted in a model with a 70% accuracy after hyperparameter tuning**. Changes were made to improve the model by another 9%. Red cars in certain census tracts were found more likely to be stolen. We also found certain makes and models of vehicles are more likely to be stolen depending on the socio-economic status of the census tract. With that information, the CMPD could then make more concentrated efforts at certain census tracts.

Below is an image of the vehicle related crimes mapped over mecklenburg census tracts with the distinction in either private or non private residence.
![CMPD](/assets/img/output.png)

### 2. School EOG Scores with Power Bi/Excel/Python
[Link](https://www.linkedin.com/posts/mahmoud-alhousseiny-613004151_i-recently-took-part-in-a-second-round-interview-activity-7210690177705357313-5M1l?utm_source=share&utm_medium=member_desktop)

As part of the 3nd round interview for the position of senior data analyst at CMS, I was tasked with creating a presentation using tools such as power bi, excel, python, and powerpoint. The goal was to analyze past years End of Grade (EOG) scores for students in NC and use that data to predict future years performances. With a **r^2 value of 0.72**. I was able to reasonably predict the 2024-2025 school year EOG performances after using **ridge regression and ANOVA testing**. The presentation involved a LIT review, before understanding and cleaning the data. The data was then transformed using a mixture of Power Bi and Excel. The spatial analysis was conducted in Python. Some insights gained included, male and female students perform similarly. Post COVID-19, most students EOG scores rebounded to pre COVID-19 years. Minority students EOG scores decreased the most during COVID-19.

Below is an image that showcases the spatial analysis done to find the top 5 school districts with the highest percentage of students achieving a score of not proficient.
![CMS](/assets/img/spatial_analysis.png)

Below is an image that compares all student subgroups and their performance levels.
![CMS](/assets/img/compare.png)

### 3. Pytorch Job Applications Bot (NLP and Deep Learning)
![DeepLearning](/assets/img/deep_learning.png)
Using **NLP and web scrapping**, I created an application with the ability to apply to Linkedin easy apply positions. This utilized the pytorch for deep learning inorder to construct the application. The application is easily customizable by simply editing a json for a better user experience.


## Certifications

Data Analyst Associate – Data Camp        [Link](www.datacamp.com/certificate/DAA0014437719902)

Data Specimens Only Research – CITI Program	
