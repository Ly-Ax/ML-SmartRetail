# Smart Retail: Sales & Profits of a Superstore

## Dataset

> Context

With growing demands and cut-throat competitions in the market, a super store is seeking understanding what works best for them. They would like to understand which products, regions, categories and customer segments they should target or avoid.

> Links

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

https://www.kaggle.com/datasets/shrutigupta2495/the-real-canadian-superstore-dataset

> Metadata

|Variable|Description|
|--------|-----------|
|Row ID|Unique ID for each row|
|Order ID|Unique Order ID for each Customer|
|Order Date|Order Date of the Product|
|Ship Date|Shipping Date of the Product|
|Number of Days|Number of Shipping Days|
|Ship Mode|Shipping Mode specified by the Customer|
|Customer ID|Unique ID to identify each Customer|
|Customer Name|Name of the Customer|
|Segment|The segment where the Customer belongs|
|City|City of residence of of the Customer|
|State|State of residence of the Customer|
|Country|Country of residence of the Customer|
|Region|Region where the Customer belong|
|Product ID|Unique ID of the Product|
|Category|Category of the Product ordered|
|Sub-Category|Sub-Category of the Product ordered|
|Product Name|Name of the Product|
|Sales|Sales of the Product|
|Quantity|Quantity of the Product|
|Unit Sales|Unit Sale of the Product|
|Discount|Discount provided|
|Profit|Profit / Loss incurred|
|Shipping Cost|Shipping Cost of the Order|
|Order Priority|Order Shipping Priority|
|Unit Shipping Cost|Unit Shipping Cost|
|Profit per Unit|Profit per Unit|
|Unit Cost|Unit Cost of the Product|

## Project

    ├── data
        ├── clean
        ├── raw
            ├── super_store.csv     -> Superstore Dataset
    ├── models
    ├── notebooks
        ├── data_exploration.ipynb  -> Exploratory Data Analysis
        ├── preprocessing.ipynb     -> Data Preprocessing
    ├── src
        ├── classifier
        ├── load
        ├── train
        ├── transform
    
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    ├── requirements.txt

<!-- ```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
``` -->
