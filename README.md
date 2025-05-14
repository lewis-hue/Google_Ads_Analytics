# Product Analytics
## Google Ads Campaign Optimization Using Amplitude Analytics

This project utilizes **Amplitude**, a leading **product analytics** tool, to optimize **Google Ads** campaigns by analyzing **user behavior** and **marketing analytics**. By tracking engagement data across platforms such as **Google**, **YouTube**, and **Google Display Network**, the goal is to identify opportunities to improve conversions and cost efficiency. The focus is on actionable data that enables the optimization of the customer journey and the alignment of marketing efforts with measurable business impact, ultimately driving **customer lifetime value**.

---

## Data Ingestion

![Data Ingestion (Connecting Google Ads Account)](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Ingestion%20of%20data.png)

### Process:
The first step involves integrating my Google Ads account with **Amplitude**, enabling the collection of detailed ad performance metrics like clicks, conversions, cost, impressions, and interactions across various platforms such as **Google**, **YouTube**, and **Google Display Network**. This integration provides crucial data on user engagement, allowing for a deeper analysis of campaign effectiveness across different ad group types and targeting strategies. By leveraging this data, I can optimize ad spend, improve targeting accuracy, and refine campaign strategies to maximize conversions and ad performance.

---

## Marketing Analytics Settings

![Marketing Analytics Settings (Page View Event & Filters)](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Marketing%20Analytics%20settings%20(Page%20View%20Event%20%26%20Filters).png)

![Marketing Analytics Settings (Breakdown)](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Marketing%20Analytics%20settings%20(Breakdown).png)

![Marketing Analytics Settings (Ad Performance)](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Marketing%20Analytics%20settings%20(Ad%20Performance).png)

### Overview:
In this project, Amplitude’s marketing analytics settings are configured to optimize Google Ads campaigns by analyzing user behavior and ad performance across **Google**, **YouTube**, and **Google Display Network**. Key metrics such as clicks, conversions, cost, impressions, and interactions are tracked and segmented by ad group type, ad platform, and campaign dates. Custom filters, including **final_url** and **ad_account_id**, enable detailed breakdowns of user acquisition and page engagement. Key ad metrics like **ad_metrics.clicks**, **ad_metrics.conversions**, **ad_metrics.cost**, and **ad_metrics.interactions** provide actionable insights to enhance campaign effectiveness and optimize user journeys.

---

## Ad Performance Analysis

### Ad Clicks per Platform

![Ad Clicks per Platform](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Ad%20Clicks%20per%20Ad_Platform.png)

#### Analysis:
- **Google Display Network (GDN)** leads in total ad clicks with 17, followed by **Google Search** with 16 and **YouTube** with 12 over the past 60 days.
- GDN’s higher click count suggests it reaches a broader audience and attracts more user engagement. This is likely due to the visual nature of display ads, which perform well in remarketing campaigns.
- Google Search Ads, with 16 clicks, capture intent-driven traffic, leading to highly qualified leads.
- YouTube, with 12 clicks, plays a crucial role in brand awareness and deeper engagement, although it may not yield immediate clicks compared to other ad formats.

#### Key Implications:
- **Refining Audience Targeting:**
  - Expand targeting on GDN using **interest-based**, **behavioral**, and **lookalike audiences**.
  - Focus on **long-tail keywords** for Google Search to capture more qualified leads and filter irrelevant traffic using negative keywords.
  - Enhance targeting for YouTube by leveraging **in-market audiences** and retargeting past users. Optimize video content with strong **calls-to-action (CTAs)** to increase engagement.

- **Optimizing Ad Formats & Placements:**
  - Experiment with different ad formats on GDN, such as **responsive display ads** and **native ads**, to improve click-through rates (CTR).
  - Test **skippable ads** and **non-skippable ads** on YouTube to find the best fit for broader reach or higher impact.

- **Tracking Performance:**
  - Focus on **Cost Per Click (CPC)** and **Conversion Rate (CVR)** to evaluate platform performance. Consider reallocating budgets based on performance metrics.

---

### Ad Conversion Per Platform

![Ad Conversion Per Platform](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/AD%20Conversion%20Per%20Platform.png)

The **Google Display Network** achieved the highest total of **17 conversions**, followed by **Google** with **16** and **YouTube** with **12**. The GDN's higher ad conversion rate indicates its effectiveness in generating leads, while Google Search continues to capture high-intent traffic. YouTube, though having fewer conversions, contributes to brand awareness.

#### Key Implications:
- **Audience Targeting & Optimization:**
  - Expand targeting on GDN and adjust strategies to enhance conversions, particularly for **remarketing** campaigns.
  - Refine keyword targeting on Google Search for high-conversion, low-competition terms.
  - Use YouTube for more strategic targeting to improve engagement and conversion, leveraging video content optimized for conversion.

- **Budget Allocation & Spend Efficiency:**
  - Allocate more budget to platforms showing strong conversion rates. For instance, if GDN has a high conversion rate, consider investing further in display ads.
  - For platforms like YouTube, analyze engagement and conversions before making significant budget changes.

---

## Advertising Costs per Platform

![Advertising Costs per Platform](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Cost%20of%20Advertising%20for%20Different%20Ad%20Platforms.png)

The **Google Display Network** accounted for the highest advertising expenditure at **Ksh 4942.42**, followed by **Google Search** at **Ksh 3989.38**, and **YouTube** at **Ksh 3779.89**. The higher costs associated with GDN reflect its broad reach, while YouTube's lower cost suggests it is used for campaigns focused on brand awareness rather than direct conversions.

#### Key Implications for Budget & Spend Efficiency:
- **Optimize Spend:**
  - Reallocate budget based on performance metrics. If GDN incurs high costs but generates low conversions, consider adjusting targeting or switching budget to more efficient platforms.
  - For platforms like YouTube, analyze engagement and conversions before making significant budget changes.

---

## Clicks per Ad Group

![Clicks per Ad Group](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Clicks%20Per%20Ad%20Group.png)

### Analysis:
- **Group_6** shows the highest click rate at **16.1%**, while **Group_9** and **Group_1** have lower click rates at **6.9%**.
- **Group_6** should expand its targeting to capitalize on its success, while **Group_9** and **Group_1** require further optimization in targeting and creatives.

#### Key Implications for Ad Group Optimization:
- **Targeting Refinement:**
  - Expand targeting for **Group_6** to replicate its success across similar groups.
  - For **Group_9** and **Group_1**, refine targeting by reviewing ad creatives, keywords, and demographics.

- **Creative Optimization:**
  - **Group_6**'s success should be analyzed for effective ad creatives and messaging. Apply these insights to other underperforming groups.
  - Revise **Group_9** and **Group_1**'s ad copy and visuals to improve click performance.

---

## Interactions per Ad Group Type

![Interactions per Ad Group Type](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/Interactions%20Per%20Ad%20Group%20Type.png)

The **Search** ad group type has the highest interaction count (7), followed by **Video** and **Display** with 4 interactions each. Search ads perform well in terms of user engagement due to their intent-driven nature. Video and Display ads need more refinement to increase meaningful interactions.

#### Key Implications:
- **Refine Targeting for Search Ads:** Continue targeting high-intent keywords and leverage **negative keywords** to filter out irrelevant traffic.
- **Optimize Video Ads:** Focus on targeting users likely to engage, using **retargeting** and **lookalike audiences** to improve interaction rates.
- **Improve Display Ads:** Refine targeting and use **dynamic display ads** that adapt based on user behavior to improve interaction.

---

## Conclusion & Dashboard

### AD Conversion per Platform (Dashboard)
![Dashboard](https://github.com/lewis-hue/Google_Ads_Analytics/blob/main/AD%20Conversion%20Per%20Platform%20(Dashboard).png)

By continuously optimizing ad targeting, creative content, and spend allocation, it is possible to enhance the overall effectiveness of Google Ads campaigns. Ongoing analysis and adjustments are key to driving better conversions and maximizing return on investment (ROI).
