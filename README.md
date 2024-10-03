# Data Scientist & Data Analyst

#### Summary

Current data analyst with 4 years of experience, seeking an analyst role with expertise in data collection, analysis, and reporting. Additional focus on verbal and written communication skills with a track record of working in collaborative team environments. Increased annual revenue of a record distribution company by 8% in 2023 by collaborating with the product management team and performing cohort analysis. Skilled in data validation, handling inquiries, creating scheduled/ad hoc reports, and data visualization. A proven track record in enhancing data infrastructure and providing reports to stakeholders.

#### Technical Skills: Python, SQL, AWS, R, MATLAB, Azure, Power Bi, Excel, CSS, HTML, Git

## Education

- Bachelors of Science, Data Science | The University of North Carolina at Charlotte (_May 2024_)
- Associates, Computer Science | Central Piedmont University (_May 2022_)

## Work Experience
**Data Analyst – 33 1/3 Record Distribution (_May 2020 - April 2024_)**
- Analyze extensive customer sales data to develop insightful PowerBI dashboards and visualizations.
- Collaborated with the product management team to perform cohort analysis, leading to pricing strategies that increased annual revenue by 8% in 2023.
- Created structured SQL databases (MySQL) for data storage, management, and inquiries, documenting processes, SQL queries, and stored procedures.
- Leveraged excel functions, including VLOOKUPs, XLOOKUPs and pivot tables, to simplify analysis and reporting processes.

## Projects
### Policing with Predictive Modeling
[Link](https://github.com/Hippobot/Policing-with-Predictive-Modeling/tree/main)

In 2022, the Charlotte Mecklenburg Police Department gave out a complex data set spanning multiple years which detailed all sorts of crimes, locations, and many other criteria. The dataset was non anonymized while also having close to 1 million rows and 100s of features (columns). The dataset was not clean and lacking any rubric/legend to reference for the column labels. I was tasked to see if I can bring any insights to the table from this dataset and present to the relevant stakeholders. I led a team of 4 of my peers to publish a report on the CMPD data and construct an XG-Boost classification model to predict vehicle crime from car characteristics (model, make, color, etc). ArcGIS was used to spatially join the shape files to the csv police dataset and create distance buffer zones. Excel was used to clean and organize the data, then used python to initialize everything. This resulted in a model with a 70% accuracy after hyperparameter tuning. Changes were made to improve the model by another 9%. Red cars in certain census tracts were found more likely to be stolen. We also found certain makes and models of vehicles are more likely to be stolen depending on the socio-economic status of the census tract. With that information, the CMPD could then make more concentrated efforts at certain census tracts.

Below is an image of the vehicle related crimes mapped over mecklenburg census tracts with the distinction in either private or non private residence.
![CMPD](/assets/img/output.png)

### Pytorch Job Applications Bot (NLP and Deep Learning)
![DeepLearning](/assets/img/deep_learning.png)
Using NLP and web scrapping, I created an application with the ability to apply to Linkedin easy apply positions. This utilized the pytorch for deep learning inorder to construct the application. The application is easily customizable by simply editing a json for a better user experience.
