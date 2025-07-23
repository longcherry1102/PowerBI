# Amazon Sales Dashboard

An interactive Power BI dashboard for exploring Amazon sales data, revealing key insights into revenue, products, customers, and order fulfillment.

---
## Live Dashboard

<a href="https://longcherry1102.github.io/amazon_sales/" target="_blank"><b>View Live Dashboard Here</b></a><br>
(Replace `https://your-username.github.io/amazon_sales/` with your actual GitHub Pages URL)

---

## Dataset Description

The `amazon_sales_data_2025.csv` file contains 250 rows of simulated Amazon order data. This dataset is a valuable resource for understanding various aspects of e-commerce performance, allowing for analysis of sales trends, product popularity, customer purchasing habits, and order processing efficiency.

---

## Column List

Here's a breakdown of the fields in the dataset:

* **Order ID**: Unique identifier for each order (e.g., ORD0001).
* **Date**: Date of the order.
* **Product**: Name of the product purchased.
* **Category**: Product category (e.g., "Electronics", "Clothing", "Home Appliances", etc.).
* **Price**: Price of a single unit of the product.
* **Quantity**: Number of units purchased in the order.
* **Total Sales**: Total revenue from the order (`Price × Quantity`).
* **Customer Name**: Name of the customer.
* **Customer Location**: City where the customer is based.
* **Payment Method**: Mode of payment (e.g., "Credit Card", "Debit Card", "PayPal", etc.).
* **Status**: Order status (e.g., "Completed", "Pending", or "Cancelled").

---

## Getting Started

Follow these simple steps to get the dashboard up and running:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/amazon-sales-dashboard.git](https://github.com/your-username/amazon-sales-dashboard.git)
    ```
    (Replace `https://github.com/your-username/amazon-sales-dashboard.git` with the actual repository URL)

2.  **Place the data file:**
    Move the `amazon_sales_data_2025.csv` file into the `data/` directory within the cloned repository.

3.  **Open in Power BI Desktop:**
    Open the `Amazon_Sales.pbix` file using Power BI Desktop. The report should automatically connect to the CSV data.

---

## How to Use

Navigate through the following report pages to gain insights:

* **Overview**: Get a high-level summary of key sales metrics, including total revenue, total orders, and overall sales trends.
* **Trends**: Explore revenue and order trends over time, allowing you to identify seasonal patterns or growth areas.
* **Category/Product**: Dive into the performance of different product categories and individual products, identifying top sellers and underperforming items.
* **Customer Insights**: Understand customer behavior, including top customers and purchasing patterns.
* **Order Status**: Monitor the status of orders, providing insights into fulfillment efficiency and identifying potential bottlenecks.

---
---

## Contributing

We welcome contributions! If you have ideas for new analyses, visuals, automations, or find any issues, please feel free to:

* Open an issue to report bugs or suggest enhancements.
* Submit a pull request with your proposed changes.

---

## License

This project is licensed under the MIT License.
