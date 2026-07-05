Dataset Description

The dataset contains transaction history, product pricing, customer demographics, and store types, which allows for an in depth look at multi-channel retail dynamics. It consists of four main interconnected tables:
--> customer: Contains profile details of registered customers, including their id, city of residence, email domain used, and gender.
--> product: Lists the available products by id along with their unit price.
--> store: Defines the purchasing channels (id and type), ranging from Offline stores, Online stores, Partnerships, to special Events.
--> transaction: The core fact table recording each purchase. It includes id, links to other tables (store_id, customer_id, product_id), quantity purchased, total amount paid, and the timestamp (created_at).

Conclusion and Recommendations

Based on the cross-sectional behavioral patterns and performance metrics extracted from my datasets, here is a detailed, structured breakdown of the Conclusions and Strategic Recommendations for this retail business.

In-Depth Conclusions

A. Channel Performance & Strategy
--> Online is the Core Engine: Online stores heavily dominate the transactional volume (accounting for roughly 80% of all customer purchases regardless of gender). This indicates high digital adoption, a seamless web/app experience, or a highly effective digital marketing funnel.
--> Offline is for Value, Online is for Frequency: While Online drives volume, physical "Offline stores" remain crucial. Brick-and-mortar locations account for around 17-18% of transactions but traditionally yield a higher basket size or higher average order value (AOV) per physical visit, as customers physically interact with products.
--> Underperforming Tail Channels: Partnership stores and special Events collectively make up less than 3% of total transaction volume. Currently, these channels are not serving as scalable growth drivers, meaning they either lack visibility or carry inventory that doesn't appeal to your core audience.

B. Customer & Geographic Profiling
--> Homogeneous Gender Demographics: There is almost a perfect 50/50 split in transactional behavior between Male and Female shoppers across all store types. Gender does not dictate where someone shops in this dataset; convenience (Online vs. Offline) dictates it.
--> Regional Powerhouses: Spending is highly concentrated in metropolitan centers like Jakarta, followed closely by satellite cities such as Depok, Tangerang, and Bogor. Jakarta represents the highest concentration of high-value, high-frequency buyers.

C. Temporal Dynamics & Shopping Habits
--> Operational Peak Hours: Customer transactional activity follows distinct daily operational waves (e.g., lunch breaks or post-work hours).
--> Growth Fluctuation: The data from May to December 2018 indicates clear month-over-month fluctuations, highlighting that retail performance is heavily dependent on specific cyclical retail calendar events (such as pay-day periods or year-end holidays).

Strategic Recommendations
To turn these data insights into business growth, management should execute the following actions:

1. Double-Down on Digital Personalization (Online Channel)
Since 80% of your audience interacts with your Online store, small improvements in online conversions will result in massive revenue increases.

Action: Implement an automated product recommendation engine on your app or website. Since you have customer_id tied to specific product_id purchases, use collaborative filtering to suggest "frequently bought together" items at checkout to increase online transaction values.

2. Re-engineer the Purpose of Offline Stores
Physical stores should no longer try to compete with the sheer volume of Online stores. Instead, pivot their purpose toward experiential retail.

Action: Treat physical stores as "Showrooms" where high-end or high-margin products can be sampled. Use click-and-collect (Buy Online, Pick Up In Store - BOPIS) features to bridge the gap, driving digital users into physical stores where staff can cross-sell accessories.

3. Hyper-Local Geographic Target Marketing
Stop spending marketing budgets uniformly across the country. Focus strictly on regional hubs that yield real volume.

Action: Shift 70% of digital ad spend (Google Ads, Social Media geo-targeting) directly onto Jakarta and Depok custom audiences. For lower-performing regions, run local awareness campaigns rather than direct conversion ads.

4. Restructure Partnerships and Events
Partnerships and Events are currently operational overheads with minimal return.

Action: Set strict performance benchmarks for third-party partnerships. If partnership volumes do not increase within the next quarter, phase them out and reallocate that capital to strengthen the server infrastructure or UI/UX of the Online store.

5. Workforce and Server Optimization (Temporal Alignment)
Align business costs directly with the hourly and monthly peaks discovered in your trend analysis.

Action: Scale down cloud server capacities during low-traffic midnight hours to cut IT operational costs. Conversely, prepare automated email marketing pushes and ensure customer support is fully staffed precisely during the identified daily peak afternoon/evening shopping windows.
