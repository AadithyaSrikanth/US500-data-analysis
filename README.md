# US500-data-analysis
## Data analysis of US500 dataset using Pandas

# Intoduction

Our dataset is based on the companies in USA. It provides various information ranging from year founded in a city to its business model, source of revenue and impact on the society. It’s a comprehensive dataset to analyze the various trends of the corporate world and how it affects employability and economy of the city.

The features include both numeric and non-numeric data. Numeric data includes ‘year_founded’, ‘zip_code’ and ‘last_updated’. The remaining 19 columns are non-numeric which gives description of the company, its type, category and its revenue source.

We have described the process of choosing the features by clearly stating the reasons for the same followed by cleaning to ensure smooth analysis. The columns we selected are ‘company_name’, ‘year_founded’, ‘city’,’state’, ‘full_time_employees’,’company_type’,’company_category’,’revenue_source’,’business_model’,’description’ and ‘description_short’.

We have converted ‘full_time_employees’ to numeric value to perform mathematical analysis such as to obtain the distribution across various cities, types and categories.

We have framed appropriate questions to extract meaningful insights into the data. We were able to get convincing results centered on preferred city, state for a company of a particular type and category and its impact on employability and emergence of different trends.

We have applied machine learning algorithm of multivariate logistic regression using Random Forest Classifier to predict ‘company_category’ by appropriately selecting features. The text features ‘business_model’, ‘description’ and ‘description_short’ have been combined to reduce dimensions. Text pre-processing has been applied to get the embeddings. TF-IDF technique has been applied to quantify the text data. Categorical numeric values have been assigned to ‘city’, ‘state’ and ‘company_category’ which is the predicted variable. ‘year_founded’ and ‘employees’ has also been included as numeric features. We obtained an accuracy of
61%

