# Combining-Multiple-Subscriptions-Tables
In this query, we're 🎨 creating a blend 🌟 of active subscriptions from two distinct products. We then take a step back in time ⏪ by dissecting these subscriptions 🔍, grouping them by year 📅, and counting how many have graced our presence each year 📈. It's all about dissecting the data's historical patterns. 📊🕰️

🤔 Business Problem:
The Chief Growth Officer of a car share company is laser-focused on minimizing the number of customers who don't renew their annual subscriptions. The company offers two types of subscriptions, and due to data modeling constraints, they couldn't be placed in the same table.

💡 Our mission? 
We need to merge both products into our annual counts to accurately measure customer activity.
🔍 We're embarking on a journey to tally the number of expired subscriptions by year, enabling us to craft an insightful report on the status of these subscriptions.

❓ Questions:
Which year records a higher count of inactive subscriptions?
How many active subscriptions can we deduce from the total subscriptions?


💡 Insights:
🧐 Activity Dip in 2023: In 2023, we observed a decline in activity. Non-active subscriptions increased compared to the previous year, hinting at changes during this time.

🚫 80% User Activity: Currently, 8 out of 10 users are actively engaging with the app. However, we've experienced a loss of 1 out of 10 active users compared to the previous year.

📈 Binary Count for Insight: Given this data scenario, utilizing a binary count system where 1 represents active and 0 represents inactive can offer a simplified approach for assessing qualitative data. 🛠️🔍
