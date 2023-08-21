# **Retail Customer Segmentation with RFM Analysis**

## **Introduction**

Welcome to the Retail Customer Segmentation project! In this repository, we perform an RFM (Recency, Frequency, Monetary) analysis on retail store customer data obtained from the UCI Machine Learning Repository. This analysis is followed by customer segmentation using the K-means clustering algorithm to gain insights into customer behavior and enables data-driven marketing strategies.

## **Dataset**

The dataset used in this project comprises the following columns:

- **StockID**: Identifier for items purchased.
- **InvoiceNo**: Unique identifier for each purchase transaction.
- **CustomerID**: Unique identifier for each customer.
- **InvoiceDate**: The date of the purchase transaction.
- **UnitPrice**: The price of each item.
- **Quantity**: The number of items purchased.
- **Country**: The country where the purchase was made.
- **Description**: The name of the purchased item.

The dataset provides a comprehensive view of customer transactions, allowing us to perform meaningful RFM analysis and segmentation.

## **RFM Analysis**

![Alt text](rfm-intro.png?raw=true "Title")


RFM analysis is a customer segmentation technique that leverages three key metrics:

1. **Recency (R)**: How recently a customer made a purchase. It measures customer engagement and loyalty.
2. **Frequency (F)**: How often a customer makes purchases. It indicates customer activity and buying patterns.
3. **Monetary (M)**: The total amount a customer has spent. It quantifies the customer's value to the business.

By calculating these metrics for each customer, we gain valuable insights into their behavior. For example, a customer with high recency, frequency, and monetary value is considered a loyal and valuable customer.

## **Customer Segmentation**

![Alt text](RFMCluster.png?raw=true "Title")

To segment customers effectively, we employ the KMeans clustering algorithm. KMeans groups customers into clusters based on their RFM values, allowing us to identify distinct customer segments. These segments can then be targeted with tailored marketing strategies.

The key steps in the customer segmentation process include:
- Preprocessing the data.
- Determining the optimal number of clusters using techniques like the elbow method.
- Applying KMeans clustering.
- Analyzing and interpreting the results.

## **Usage**

To run the code and replicate the analysis, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the Jupyter Notebook `customer_segmentation.ipynb`.

The notebook contains detailed explanations and code for each step of the analysis.

## **Results**

The results of the customer segmentation analysis are presented in the Jupyter Notebook. The clusters identified can be used for targeted marketing campaigns, product recommendations, and customer retention strategies.

Here are some potential actions based on the segments:
- **High-Value Customers**: Offer loyalty rewards or personalized product recommendations.
- **Potentiol loyalists**: Upsell higher-margin products.
- **Hibernate Customers**: Encourage them to make more frequent purchases with discounts or promotions.

By leveraging these insights, businesses can optimize their marketing efforts and ultimately improve their bottom line.

## **Contributing**

Contributions to this project are welcome! If you have ideas for improvements or new features, please feel free to submit issues or pull requests.

---

Thank you for exploring our Retail Customer Segmentation project. We hope you find the insights and code valuable for your data-driven marketing initiatives. If you have any questions or feedback, please don't hesitate to reach out!

[![GitHub](https://img.shields.io/badge/GitHub-Connect-blue)](https://github.com/amirmahdi-alavi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/amirmahdi-alavi)

Happy analyzing and segmenting! 🛍️📊🎯
