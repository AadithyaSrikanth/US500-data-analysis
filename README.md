# US500-data-analysis
## Data analysis of US500 dataset using Pandas

### T9:

### Context
The Open Data 500, funded by the John S. and James L. Knight Foundation (http://www.knightfoundation.org/) and conducted by the GovLab, is the first comprehensive study of U.S. companies that use open government data to generate new business and develop new products and services.

### Study Goals
Provide a basis for assessing the economic value of government open data

Encourage the development of new open data companies

Foster a dialogue between government and business on how government data can be made more useful

The Govlab's Approach
The Open Data 500 study is conducted by the GovLab at New York University with funding from the John S. and James L. Knight Foundation. The GovLab works to improve people’s lives by changing how we govern, using technology-enabled solutions and a collaborative, networked approach. As part of its mission, the GovLab studies how institutions can publish the data they collect as open data so that businesses, organizations, and citizens can analyze and use this information.

Company Identification
The Open Data 500 team has compiled our list of companies through (1) outreach campaigns, (2) advice from experts and professional organizations, and (3) additional research.

Outreach Campaign

Mass email to over 3,000 contacts in the GovLab network

Mass email to over 2,000 contacts OpenDataNow.com

Blog posts on TheGovLab.org and OpenDataNow.com

Social media recommendations

Media coverage of the Open Data 500

Attending presentations and conferences

Expert Advice

Recommendations from government and non-governmental organizations

Guidance and feedback from Open Data 500 advisors

Research

Companies identified for the book, Open Data Now

Companies using datasets from Data.gov

Directory of open data companies developed by Deloitte

Online Open Data Userbase created by Socrata

General research from publicly available sources

What The Study Is Not
The Open Data 500 is not a rating or ranking of companies. It covers companies of different sizes and categories, using various kinds of data.

The Open Data 500 is not a competition, but an attempt to give a broad, inclusive view of the field.

The Open Data 500 study also does not provide a random sample for definitive statistical analysis. Since this is the first thorough scan of companies in the field, it is not yet possible to determine the exact landscape of open data companies.

Shape of the Data Set (529, 22)

# Intoduction

Our dataset is based on the companies in USA. It provides various information ranging from year founded in a city to its business model, source of revenue and impact on the society. It’s a comprehensive dataset to analyze the various trends of the corporate world and how it affects employability and economy of the city.

The features include both numeric and non-numeric data. Numeric data includes ‘year_founded’, ‘zip_code’ and ‘last_updated’. The remaining 19 columns are non-numeric which gives description of the company, its type, category and its revenue source.

We have described the process of choosing the features by clearly stating the reasons for the same followed by cleaning to ensure smooth analysis. The columns we selected are ‘company_name’, ‘year_founded’, ‘city’,’state’, ‘full_time_employees’,’company_type’,’company_category’,’revenue_source’,’business_model’,’description’ and ‘description_short’.

We have converted ‘full_time_employees’ to numeric value to perform mathematical analysis such as to obtain the distribution across various cities, types and categories.

We have framed appropriate questions to extract meaningful insights into the data. We were able to get convincing results centered on preferred city, state for a company of a particular type and category and its impact on employability and emergence of different trends.

We have applied machine learning algorithm of multivariate logistic regression using Random Forest Classifier to predict ‘company_category’ by appropriately selecting features. The text features ‘business_model’, ‘description’ and ‘description_short’ have been combined to reduce dimensions. Text pre-processing has been applied to get the embeddings. TF-IDF technique has been applied to quantify the text data. Categorical numeric values have been assigned to ‘city’, ‘state’ and ‘company_category’ which is the predicted variable. ‘year_founded’ and ‘employees’ has also been included as numeric features. We obtained an accuracy of
61%

