# Predicting eCommerce Behavior Using Clickstream Data
This project presents a case study on how machine learning can help solve business problems. The business problem in this case is **online shopping cart abandonment** which happens when a customer adds one or more items to their *cart* but leaves the online store without completing the purchase. To solve this, a binary classifier was developed to predict whether a customer will abandon their cart based on their behavior on the platform.

## Data Source
The dataset that contains anonymized eCommerce behavior data from a multi-product category store. The dataset is hosted on [Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store) and was provided by [REES46 Technologies](https://rees46.com/) through their [open source customer data platform](https://rees46.com/en/open-cdp).

The data is uploaded in CSV format and measures 14.66 GB. It contains 109,950,743 instances, each representing a single event (view, add to cart, purchase) made by a user on the platform. 

The dataset contains 9 features:

* **event_time** (datetime): The time when the event happened in UTC.
* **event_type** (string): The type of event (action taken by the user). 
    * Types: 
        * *view* (a user viewed a product)
        * *cart* (a user added a product to the shopping cart), and 
        * *purchase* (a user purchased a product)
* **product_id** (integer): ID of the product.
* **category_id** (integer): ID of the product category.
* **category_code** (string): The category taxonomy of the product.
* **brand** (string): Brand name of the product.
* **price** (float): Current price of the product.
* **user_id** (integer): Permanent ID of each user.
* **user_session** (string): Temporary session ID of each user when they use the platform. This changes every time the user revisits the platform after a long pause. This can have multiple events as a user could perform different events during one session.

## Methods Applied
* Descriptive Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* Binary Classification

## Libraries Used
* Scikit-learn
* XGBoost
* Pandas
* NumPy
* Matplotlib
* Seaborn


