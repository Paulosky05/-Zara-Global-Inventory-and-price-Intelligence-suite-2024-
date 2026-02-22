#  Zara-Global-Inventory-and-price-Intelligence-suite-2024-

## Project overview
This project delivers a comprehensive 2024 inventory analysis for zara, focusing on the intersection of pricing strategy and market segmentation. Build in tableau, the dashboard provides a high-level executive view while allowing for deep-dive product analytics

## Project Objectives
### Buisness Objectives 
- identify revenue drivers
- Analyze pricing Architecture
- Optimize Product Positioning
- EStablish Price Leadership

  ### Technical Objectives
 - Architect an Integrated UX
 - Ensure Data Integrity
 - Develop Responsive Visualisations
 - Create calculated fields and parameters to dynamically group products by price leadership and popularity metrics
 
  ## Data Sources
  - Zara : The primary dataset used for this analysis is the 'Zara Fashion products Dataset (US)-2024', containing detailed information about zara fashion sales for the year 2024.

    ### TOOLS
 - Excel use for data cleaning [download-here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
 -  Tableau - Creating dashboard [down-here](https://www.tableau.com/products/desktop/download%20public)
   
   ### Data Cleaning/Preparation
  In the initial data prepation phase, we perform the following tasks:
  1. Data loading and inspection,
  2. checking for missing values.

  ### Explanatory Data Analysis
 - price leadership board
 - Section split
 - Price Distribtion
 - Revenue calculation
 - price vs popularity
 
    ## Calculated field
    ``` sql
    Price Segmentation
    IF [price] < 30 THEN "Budget"
    ELSEIF [price] <= 70 THEN "Mid Range"
    ELSE "Luxury/Premium"
    END
    ```
  ```
     Revenue Calculation
     sql
    [Price] * [Sales Volume]
 ```

   ##  Result Finding
    
   ### The premium Appeal

 Even Though Zara is known for fast fashion, the data shows that their highest-priced items are often the most liked. Instead of price scaring people away ,it seems that for zara,a higher price tag is signsl of quality that customers actually chase

 - The Execuive Gap
    When you look at the middle of the pack, most items are priced around $ 65. However, when you look at the mathematical average, it jumps way up to 80$
    why? This tells us there is a small group of "Luxury" items (like leather jackets or high end coats) that are so expensive they make the whole brand look pricier than it actually is for the average shopper

- Fashion is more than just price tag
    our data proves that price is the only a tiny part of the story. most of the reason an item sells has nothing to do with weather its cosst $20 or $50
    . Instead sales are likely driven by "The trend Factor."Is it a holiday season? Is the item "in" right now? is it the colour for the season
    . In short: Zara customers buy what is fashionable first, and check the price second

- Inventory "Danger Zones"
    By looking at the "Spread" of the data, we found that the luxury/premium section is the most unpredictable section is the most unpredictable.
    . Budget items sell at a steady, predictable pace.
    . Luxuary items are "all or nothings"- they either sell out instantly or sit on the shelf for a long time. This is the area where the store takes the biggest risk.

 ## Key Takeaways:
Branding Over Price: The analysis reveals that Zara’s brand equity is strong enough to support high engagement in premium price tiers. Customers are motivated by style and perceived value rather than simply looking for the lowest price.

Operational Health: Through a rigorous data audit, I ensured that all sections—specifically the Women’s category—were accurately represented, providing a true 360-degree view of the inventory.

Strategic Predictability: While pricing is a factor, the "Trend Factor" remains the king of sales. Success for Zara lies in mastering seasonal timing and inventory distribution across their different price segments.

Risk Management: The project highlights that while "Budget" items provide a stable foundation, the "Premium" segment is where the highest growth potential—and highest inventory risk—resides.

## Conclusion 
This dashboard is more than a collection of charts;its is a tool for executive decision making. Itallows leadership to see exactly where their money is sitting in the warehouse and how to price future collections demand 

### Recommendation 
1 Double Down on the "Luxury" items
The data shows that higher-priced items have a strong cnnection to custmers popularity's. Zara should continue to expand its studio or limited Edition lines. These items don't just sell well- the raise the perceived value of the entire brand 

2 Tighten Control on premium Stocks
 Because the high- end  items have more swing in their sales,the company should avoid overstocking them. I recommend a scarcity model for the luxury items: produce smaller batches to maintain demands batches to maintain demand and avoid the need for deep discounts later

3 Optimize Seasonal Transitions 
The pattern in the data confirms that sales are heavily tied to the calender. To maximize profits, zara should align their logistics and shipping to ensure that winter peaks are met with full shelves in November, and immediately cleared by january to make room for spring drop.

## Author PAUL THE ANALYST
This project is part of my portfolio,showcasing my SQL and powerbi skills essential for data analyst roles.. if you have any feedback,questions or would like to collaborate feel free to get in touch!

 ** REACH ME ON LINKEDIN** [click-here](https://www.linkedin.com/in/paul-muoghalu-2b8a3b272?utm)
   😄
   🖥️


    
    
