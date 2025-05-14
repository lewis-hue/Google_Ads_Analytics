# PRODUCT ANALYTICS
## Google Ads Analytics in Amplitude

This project uses **Amplitude**, a leading **product analytics** tool, to optimize **Google Ads** campaigns by analyzing **user behavior** and **marketing analytics**. By tracking engagement data across platforms like **Google**, **YouTube**, and **Google Display Network**, we identify opportunities to improve conversions and cost efficiency. With **Amplitude**, we focus on actionable data, optimizing the customer journey, and aligning marketing efforts with measurable business impact to drive **customer lifetime value**.


### Data Ingestion
![Data Ingestion (Connecting Google Ads Account](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Total%20Revenue%20Generated%20by%20Product.png)

#### Process:
The first step involved connecting my Google Adwords account with Amplitude. This step helped provide data on ad performance metrics, including clicks, conversions, cost, impressions, and interactions across different ad platforms like Google, YouTube, and Google Display Network. This data was crucial in analyzing user engagement and the effectiveness of each ad campaign, allowing for better optimization of ad spend and targeting strategies.

### Marketing Analytics Settings
![Top-performing stores by revenue](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Top-Performing%20Stores%20by%20Revenue.png)

In this project, Amplitude’s marketing analytics settings are configured to optimize Google Ads campaigns by analyzing user behavior and ad performance across platforms like Google, YouTube, and Google Display Network. Key metrics such as clicks, conversions, cost, impressions, and interactions are tracked and segmented by ad group type, ad platform, and campaign dates. Custom filters, including final_url and ad_account_id, enable detailed breakdowns of user acquisition and page engagement. Ad metrics like ad_metrics.clicks, ad_metrics.conversions, ad_metrics.cost, and ad_metrics.interactions provide actionable insights to enhance campaign effectiveness and optimize user journeys.

#### Business Implication:
High-performing stores like Store_A and Store_D can be used as benchmarks for best practices in staffing, layout, and inventory management.

Expansion strategies may prioritize locations replicating demographics or operations of top stores.

Underperforming stores (relative to their peers) should undergo a profitability and efficiency audit.
### Revenue by Country
![Revenue by Country](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Revenue%20by%20Country.png)

#### Analysis:
The global sales distribution is diverse and competitive:

USA is the top market with over $73,000 in revenue.

India, Japan, and France represent key international contributors.

Emerging markets like Brazil, Mexico, and Australia show significant untapped potential.

#### Business Implication:
Localized campaigns in the USA can yield immediate gains due to existing traction.

India and Japan should be considered for strategic expansion, especially given their revenue parity.

Emerging markets like Brazil and Mexico might benefit from regional promotions or price-sensitive product variants.



### Databrick job Runs


# Total Units Sold by Product
![Total Units Sold](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Total_Units_Sold_by_Product%20run.png)


### Top-performing Stores by Revenue
![Top-performing Stores by Revenue](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Top-Performing_Stores_by_Revenue%20run.png)


### Revenue by Country
![Revenue by Country](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Revenue_by_Country%20run.png)

### Databrick Data Pipelines
This report provides a detailed analysis of sales data across multiple dimensions including product performance, store revenue, geographic distribution, and units sold. The objective is to uncover insights that can drive business strategy and operational efficiency.
### Sales Data Pipeline
![Sales pipeline](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Sales%20Data%20Pipeline.png)

- **Sales Data Pipeline**: [Sales Pipeline](https://adb-1725146873610557.17.azuredatabricks.net/editor/notebooks/1331195736317581?o=1725146873610557)
  
### 📦 Total Revenue by Product

| Product Name | Total Revenue ($) |
|--------------|-------------------|
| Mouse        | 74,184.22         |
| Camera       | 62,221.67         |
| Tablet       | 58,502.98         |
| Smartphone   | 54,007.33         |
| Printer      | 53,667.89         |
| Laptop       | 52,178.18         |
| Headphones   | 43,196.84         |
| Keyboard     | 41,336.30         |
| Monitor      | 40,661.80         |
| Smartwatch   | 38,458.51         |

#### 🔍 Analysis:
- The **Mouse** leads as the top revenue-generating product, driven by volume and utility.
- High-value items like **Camera**, **Smartphone**, and **Laptop** dominate the mid-to-high range.
- **Peripheral products** (Keyboard, Monitor, Smartwatch) also contribute significantly.

#### 💡 Business Implications:
- Focus marketing efforts on the top 3 products to maximize revenue.
- Bundle high-demand accessories (Mouse, Headphones) with premium items like Laptops or Tablets.
- Consider increasing the product margin or upselling strategy for mid-tier earners like Printers and Smartwatches.

---

### 🏬 Total Revenue by Store

| Store Name | Total Revenue ($) |
|------------|-------------------|
| Store_A    | 116,150.15        |
| Store_D    | 114,364.53        |
| Store_E    | 104,556.63        |
| Store_C    | 98,059.17         |
| Store_B    | 85,285.23         |

#### 🔍 Analysis:
- **Store_A** and **Store_D** lead the pack in overall revenue, closely followed by Store_E.
- Store_B, although slightly behind, still makes a strong contribution.

#### 💡 Business Implications:
- Analyze operational strategies from Store_A and Store_D to replicate success across other stores.
- Invest in marketing and staffing for mid-tier performers like Store_B to help close the revenue gap.
- Prioritize high-performing stores for product launches or promotional events.

---

### 🛒 Total Units Sold by Product

| Product Name | Units Sold |
|--------------|------------|
| Tablet       | 126        |
| Mouse        | 116        |
| Headphones   | 104        |
| Smartphone   | 101        |
| Laptop       | 96         |
| Camera       | 95         |
| Printer      | 88         |
| Keyboard     | 86         |
| Monitor      | 85         |
| Smartwatch   | 80         |

#### 🔍 Analysis:
- **Tablet** is the top-selling product by unit, indicating strong consumer demand.
- **Mouse** and **Headphones** also show high turnover, likely due to lower price points and wide use.

#### 💡 Business Implications:
- Ensure sufficient stock levels for high-turnover products to avoid missed sales opportunities.
- Use high-volume items in promotional bundles or as loss leaders to attract more customers.
- Lower-selling units like Smartwatch may need repositioning or targeted marketing to improve performance.

---

### 🌍 Total Revenue by Country

| Country   | Total Revenue ($) |
|-----------|-------------------|
| USA       | 73,420.13         |
| India     | 66,745.89         |
| Japan     | 66,123.43         |
| France    | 58,615.83         |
| Brazil    | 51,187.92         |
| Germany   | 49,148.33         |
| Australia | 48,194.62         |
| Canada    | 40,835.65         |
| Mexico    | 39,978.88         |
| UK        | 24,165.04         |

#### 🔍 Analysis:
- The **USA** is the top revenue generator, followed by **India** and **Japan**.
- Countries like **Germany**, **Australia**, and **Brazil** show strong potential for future growth.

#### 💡 Business Implications:
- Prioritize marketing and customer engagement in top-performing countries.
- Explore regional trends in mid-tier markets to unlock growth (e.g., Brazil, Mexico).
- Consider localized product variations or pricing models in underperforming markets like the UK.

---

### 📈 Average Revenue per Store

| Store Name | Average Revenue per Transaction ($) |
|------------|--------------------------------------|
| Store_E    | 2,904.35                             |
| Store_A    | 2,701.17                             |
| Store_C    | 2,650.25                             |
| Store_B    | 2,436.72                             |
| Store_D    | 2,333.97                             |

#### 🔍 Analysis:
- **Store_E** boasts the highest average revenue per transaction, indicating efficient sales per order.
- **Store_D**, despite being second in total revenue, has the lowest average—suggesting high volume with lower-value transactions.

#### 💡 Business Implications:
- Focus on **Store_E**’s sales tactics or product mix to improve efficiency across other stores.
- Increase upselling and cross-selling in Store_D to boost average transaction value.
- Reward or incentivize high-ticket sales to push other stores toward Store_E’s benchmark.

---

## ✅ Summary

This analysis provides clear guidance on where to focus sales, marketing, and operational strategies:

- **High-value products and stores** should be prioritized for revenue growth.
- **Popular products by units sold** are ideal for promotional strategies.
- **Regional revenue differences** can guide targeted international marketing.
- **Per-store metrics** help benchmark performance and optimize operations.

### Databrick Data Visualization

### Sales Dashboard (Databricks)
![Sales Dashboard](https://github.com/lewis-hue/BusinessIntelligence/blob/main/Sales%20Dashboard%20(Databricks).png)

- **Sales Dashboard (Databricks)**: [Sales Dashboard](https://adb-1725146873610557.17.azuredatabricks.net/dashboardsv3/01f0144f8e891796b011d102c979064a/published?o=1725146873610557)
```{r}
