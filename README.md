# MongoDB-Atlas-Project
## About Dataset<br>

In Europe bikes dataset , Extract the insight of sales in each country and each state of their countries.<br>
In this dataset 18 columns and main column is sales.<br>
[Dataset](https://www.kaggle.com/datasets/sadiqshah/bike-sales-in-europe)<br>

### Column description:
- Date: The specific calendar date of the transaction.<br>
- Day: The day of the week the transaction occurred.<br>
- Month: The month when the transaction took place.<br>
- Year: The year of the transaction.<br>
- Customer_Age: The age of the customer making the purchase.<br>
- Age_Group: The categorized age range of the customer (e.g., Youth, Adults, etc.).<br>
- Customer_Gender: The gender of the customer (M for Male, F for Female).<br>
- Country: The country where the transaction occurred (e.g., Canada, Australia, etc.).<br>
- State: The specific state within the country where the transaction happened.<br>
- Product_Category: The broad category of the product sold (e.g., Accessories, Bikes, etc.).<br>
- Sub_Category: A more detailed classification of the product (e.g., Helmets, Jerseys, etc.).<br>
- Product: The specific product sold, identified categorically.<br>
- Order_Quantity: The number of units of the product purchased in the transaction.<br>
- Unit_Cost: The cost per unit of the product to the seller.<br>
- Unit_Price: The price per unit of the product for the customer.<br>
- Profit: The monetary gain from the transaction (Revenue - Cost).<br>
- Cost: The total cost incurred by the seller for the order (Order_Quantity × Unit_Cost).<br>
- Revenue: The total money earned from the transaction (Order_Quantity × Unit_Price).<br>

## Dashboard
![Atlas_Project](https://github.com/user-attachments/assets/ff6cfd0f-4046-4b45-bd41-6d6119614159)

### Questions<br>
1. Which age group contributes the most revenue to the business product category wise?<br>
![image](https://github.com/user-attachments/assets/9ffd9a56-ae99-48f2-adf9-e121870607fe)
The graph shows that **Adults (35-54)** generate the highest revenue across all product categories, with **Bikes** being the dominant contributor, followed by **Accessories and Clothing**. **Young Adults (25-34)** rank second in revenue, while **Youth (<25)** contribute the least. This indicates that marketing efforts should focus on **Adults** and enhancing engagement with the **younger age group**.<br>

2. How has the revenue trended over time compared to profit?<br>
![image](https://github.com/user-attachments/assets/45d90c69-a410-489d-b149-b856a545775e)
The graph shows that revenue is consistently higher than profit over time, with significant fluctuations in both. A notable gap exists between revenue and profit, suggesting high operating costs or expenses. Further analysis is needed to identify opportunities for profit optimization.<br>

3. Which state generates the highest profit, and which product category contributes the most to it?<br>
![image](https://github.com/user-attachments/assets/02d279e2-2d23-4bf7-b718-6c3aa66fea9f)
**California** generates the highest profit, driven by **Bikes**, followed by **Accessories**. Other top states, including **England** and **British Columbia**, show a similar trend with **Bikes** dominating profitability. Focusing on **bike sales** in these regions can maximize returns.<br>

4. What are the top 5 sub-categories by profit margins, and how do they compare?<br>
![image](https://github.com/user-attachments/assets/aaedf828-8699-4cb4-a73b-004590165854)
The key insight is that **Touring Bikes** dominate profit margins, contributing the highest value of **₹10,078,875**, followed by **Mountain Bikes** at **₹8,160,463**. Other categories, like **Helmets**, **Tires and Tubes**, and **Road Bikes**, have relatively lower profit margins. This indicates the need to focus on the most profitable categories, particularly **Touring Bikes**, to drive profitability further.<br>

5. Which states have the highest sales revenue for the top 6 products?<br>
![image](https://github.com/user-attachments/assets/991844fc-7219-4334-bb99-fca8e6145400)
**British Columbia** and **Moselle** stand out with the highest revenue across multiple products, particularly **Road-150 Red** and **Mountain-200** series. Other states show moderate sales, indicating a need to focus efforts on these top-performing regions and products for better overall revenue.<br>

6. What are the key regions for further investment and growth opportunities?<br>
![image](https://github.com/user-attachments/assets/f8eefe95-a4dd-422b-b7c4-700fcaa4d82e)
The map highlights Country-wise Profit, with **Canada** and the **United States** showing the highest profitability, followed by select regions in **Europe**. These countries are key profit drivers and should be prioritized for business expansion and resource allocation.<br>

7. How do different product types compare in revenue contribution?<br>
![image](https://github.com/user-attachments/assets/8583f0d8-ce37-4419-a896-a54223e350b2)
This word cloud highlights the top products by revenue, emphasizing items like the **Mountain-200 Black** and **Road-150 Red**, which stand out as major revenue drivers.<br>

8. What proportion of total revenue is contributed by profit, and how does the average unit cost compare to the average unit price?<br>
![image](https://github.com/user-attachments/assets/1cc8b4e6-55f7-4a27-bdf4-e0963591e6c0)
![image](https://github.com/user-attachments/assets/87b13110-479b-4901-b614-97926482b123)
The profit represents **32,221,100** out of the total revenue, indicating a significant contribution to overall earnings.<br>
The average unit cost is **267.30**, forming a significant proportion of the average unit price of **452.94**.<br>

### Managerial Insights<br>
- Targeted Marketing and Customer Engagement<br>
  - **Focus on Adults (35–54)**: This age group generates the highest revenue across all product categories, particularly in Bikes, Accessories, and Clothing. Allocate marketing resources to campaigns targeting Adults, emphasizing premium bike models and related accessories.<br>
  - **Engage Younger Age Groups**: Youth (<25) contribute the least revenue, suggesting an opportunity to design campaigns and products tailored to their preferences, such as budget-friendly options or innovative designs.<br>

- Region-Specific Investment Strategies<br>
  - **Maximize Returns in High-Profit Regions**: Focus on expanding operations in California, British Columbia, and England, which generate the highest profits. Prioritize inventory and marketing for Bikes in these regions.<br>
  - **Develop Potential in Emerging States**: States with moderate sales, such as Moselle, could benefit from increased promotional efforts, particularly for top-performing products like the Mountain-200 and Road-150 series.<br>

- Optimize Product Portfolio for Profitability<br>
  - **Promote High-Margin Products**: Touring Bikes and Mountain Bikes dominate profit margins. Increase inventory, promotions, and strategic partnerships for these categories to boost overall profitability.<br>
  - **Streamline Lower-Margin Offerings**: Evaluate sub-categories with lower profit margins and assess the feasibility of reducing production or enhancing value propositions.<br>

- Revenue and Profit Optimization<br>
  - **Close Revenue-Profit Gap**: The significant gap between revenue and profit highlights high operating costs. Conduct a cost analysis to identify inefficiencies in manufacturing, logistics, or marketing and implement measures to optimize expenditure.<br>
  - **Leverage Pricing Strategies**: With the average unit price significantly higher than the unit cost, consider introducing price segmentation strategies (e.g., premium pricing for high-demand products) to enhance profitability.<br>

- Strategic Product Focus for Growth<br>
  - **Invest in Top-Performing Products**: Products like the Mountain-200 Black and Road-150 Red are key revenue drivers. Increase production and tailor marketing efforts around these products to sustain revenue growth.<br>
  - **Expand High-Profit Categories**: Focus on Accessories and Clothing in addition to Bikes to diversify revenue streams while maintaining profitability.<br>
