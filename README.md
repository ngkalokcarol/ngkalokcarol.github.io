Food recipe websites is a highly competitive space, where any data that could improve customer satisfaction could give an edge against competitors. In this project, we webscraped 13,000+ recipes to analyze factors that could contribute to a higher customer satisfaction measured by star ratings from 1 to 5. We pulled various attributes and performed exploratory analysis.

Screen Shot 2022-05-01 at 10 07 26 PM

Interesting findings:
• The top rated and most-reviewed recipes tend to belong to the desert category, such as chocolate chip cookies, pancakes, banana bread, muffins.
• It's possible that readers tend to gravitate towards recipes with an average cooking time of around 2-2.5 hours.
• Customers were agnostic of nutrition information and are more favorable to websites with high reviews.

Screen Shot 2022-05-01 at 10 52 27 PM

Improvement: Build a better data pipeline, including creating a table within RedShift, cleaning the table in a staging area, and then feeding the table to Spark for analysis. This would lead to higher scalability than our adhoc analysis.

Dynamic A/B Testing for Banner Optimization
Language Notebook Presentation

A/B testing is largely implemented in the market today to analyze whether or not a business decision needs to be made. Most businesses fail to review and update their "best strategy" on a regular basis due to a multitude of factors. In this project, we use a banner showing case to demonstrate how business operations can potentially benefit from continous A/B testing and dynamic strategy choosing.

Compared to the traditional A/B testing method, our solution archtecture can:
• Create streaming dashboards to visualize the results
• Constantly review the experiment & adjust setting automatically, thus reducing human's efforts
• Maximize the profits
• Potential to scale up

Big Data Architecture Screen Shot 2022-05-01 at 11 48 32 AM
