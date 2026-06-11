# Jumia Project Case Study: What Drives Product Success?


## 1. Project Overview
I built this project to figure out what actually makes a product succeed on Jumia. Using a dataset of 113 products and 725 customer reviews, I wanted to look past the surface and see how pricing, massive discounts, and customer feedback interact. To do this, I took the data through a full cleanup process and built an interactive dashboard in Excel to make the numbers easy to read and work with.

---

## 2. From Raw Data to Insights

### Cleaning Up the Data
Before jumping into charts, I had to make sure the data was clean and reliable so the final numbers wouldn't be warped:
* **Removing Duplicates:** I removed identical rows so we wouldn't double-count reviews or over-inflate product volumes.
* **Standardizing Blanks:** There were a lot of empty spaces in the reviews. I replaced these with a standard "null" marker. This was so that Excel would ignore those empty spaces and have accurate results.

### Categorizing for Better Analysis
To see the bigger picture, I grouped the raw numbers into simple categories:
* **Discount Tiers:** I grouped products by how heavily they were marked down ("High", "Medium", and "Low" discounts) to see if slashing prices actually brings in high customer reviews.
* **Sentiment Groups:** 1-to-5 star ratings into clear buckets: "Poor", "Average", and "Excellent."

### What I Looked For
I focused on three things: finding our baseline performance, tracking how discounts affect customer engagement, and separating the true top performers from products that are just heavily promoted but low quality.

---

## 3. Key Findings & Dashboard Insights

### The Big Picture Numbers
* **Total Products:** 113
* **Total Reviews:** 725
* **Average Discount:** 36.79%
* **Average Rating:** 2.00 out of 5.00

> **The Big Red Flag:** Even though products are moving and people are leaving reviews, an average rating of 2.00 is a major warning sign. It means there is a huge gap between what customers expect when they buy and what actually arrives in the mail.

### The Discount Trap
When looking at the catalog, 56% of the products fall into the "High Discount" tier. Some items, like the 8-in-1 Bottle Can Opener, have discounts as high as 70%. This suggests that sellers are clearly relying on massive price cuts just to get people to click and buy.

### What People are Actually Buying
Most of the customer feedback is concentrated in cheap, practical household tools. The 120W Cordless Vacuum Cleaner is the single most reviewed item, followed closely by baking sets and crochet kits.

### The Math: Do Discounts Actually Bring in Reviews?
I ran a correlation check to see what actually drives customer engagement, and the results were fascinating:
* **Reviews vs. Ratings ($R^2 = 0.2577$):** Products with only a handful of reviews have wild, unstable scores. But once a product crosses about 40 reviews, its rating stabilizes and usually goes up. This proves that community feedback helps people buy the right thing, leading to happier customers.
* **Discounts vs. Reviews ($R^2 = 0.0001$):** Slashing prices might get someone to hit "buy," but the size of the discount has absolutely zero impact on whether they will leave a review. True engagement comes from product quality and a good experience, not a cheap price tag.

### Extreme Opinions
The ratings show that buyers are deeply divided. "Poor" ratings make up the biggest slice of the pie at 58%, while "Excellent" sits at 22%. Almost nobody leaves an "Average" review. The items are either massive wins or massive disappointments, with no middle ground.

---

## 4. My Recommendations

* **Audit the Mega-Discounts:** Since highly discounted items make up most of the sales but also drive the massive wave of "Poor" reviews, we need to check the top 5 discounted items. Let's make sure the product descriptions aren't over-promising or misleading people.
* **Double Down on Practical Tools:** Lean into what's already working. Put more marketing focus and premium page slots toward household electronics and DIY kits—they have proven, organic demand.
* **Incentivize the First 40 Reviews:** Since more reviews statistically help stabilize a product's rating and save it from falling into the "volatile" zone, we should offer small points or discounts to buyers who leave reviews early in a product's lifecycle.
