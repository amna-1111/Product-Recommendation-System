# Product-Recommendation-System (in progress)

# **1.1. Dataset Description and Features**
# 1. Identify your dataset: Briefly describe the dataset you&#39;ve chosen. Where did you find it? What is the topic or domain?

-> The dataset contains sales data of electronic products on Amazon, sourced from Kaggle. It includes user ratings for various electronics items along with metadata such as the item's category, brand, and the timestamp of the transaction. The domain of this dataset lies in e-commerce and customer behavior analysis. (https://www.kaggle.com/datasets/edusanketdk/electronics) 

# 2. Features: List and describe the features (columns) within the dataset. What type of data is each feature (numerical, categorical, text)?

-> Features: 

The dataset includes the following features:

1. **item_id** (Numerical):   A unique identifier for each product.
2. **user_id** (Numerical):   A unique identifier for each user who purchased an item.
3. **rating** (Numerical):    The user rating given to the item (e.g., on a scale of 1 to 5).
4. **timestamp** (Text/Datetime): The date and time of the purchase. It can be converted into a datetime format for time-series analysis.
5. **model_attr** (Categorical): Despite the name, this column contains values like male and female, which suggests it may represent the gender of the user rather than item-related attributes. This is an ambiguous attribute.
6. **category** (Categorical): The category of the electronic item (e.g., Headphones, Computers & Accessories).
7. **brand** (Categorical): The brand of the item (e.g., Etre Jeune, Apple).
8. **year** (Numerical): The year of purchase, useful for trend analysis.
9. **user_attr** (Categorical): Also seems to represent user-related information.
10. **split** (Numerical): Likely used to divide data into training, validation, or testing sets. May not hold analytical value on its own.    int64

# **1.2. Preprocessing with Pandas**
