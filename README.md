# **Project Overview**

With thousands of trips happening every day and teams still struggling to see what truly drives revenue, when and where demand starts to drop, why so many bookings never turn into completed rides, and which ride options customers actually prefer and how they rate them.
This dashboard brings all ride activities into a single, clear view, showing performance by category, revenue trends, cancellations, and overall ratings from drivers and customers. It aims to help decision-makers quickly identify what is working, where money is being lost, and which ride categories and locations need more attention to improve growth and overall service quality. 

# Data Cleaning and Preparation

🔹 **Data Preparation & Transformation**

- Cleaned and transformed the dataset using Power Query to improve data quality, resolve inconsistencies, and ensure reliable analysis.
- Standardised all column names to lowercase to ensure a consistent and maintainable naming convention.
- Built DAX measures to calculate core KPIs, including total bookings, completed trips, cancelled trips, total revenue, and average distance travelled.
- Sourced and applied the official [Bolt](https://www.google.com/search?sxsrf=ANbL-n4CDQcaT1UN7ELW8HPrD4aYqjghjQ:1772185608908&udm=2&q=Bolt+logo) logo and brand [colour codes](https://www.google.com/search?q=Bolt+colour+code&sxsrf=ANbL-n5qzPEAlNOBtu2M_HOeGODteKhoQg%3A1772185665764&udm=50&aep=1&ntc=1&mstk=AUtExfAxwljPw76QlZ6Zzm213nqYYjC5RMthrb4bOT0NifejpxkSHEo2UJyP12Q8J-1HJGm1Cqs5dJHfBbq6dth-RwHauf_zGhDov0URhHY0gnF_5IIAMDblTDqrc-VxcWP73ZhWdzzofDBjGotSA5jJs05j6myiPNS126ACkyudJr3oHYBZrLx6X-hvU1m_2ox5asMs7tvDHhTkRQ6PcsRX2EJ4k8lOvuUqG0X1dl7iP16TiTkWIkJ8ws4y9AkVoCA59eJMMv5ZnmCr-afqui9iKgDwuLSxXvbdaIBerUXWt0RYCsDi7FY2lyFjpy78Ya23Hnj-_rQJ92yPKxMA4NHtDiVMZz-Gqrv63g&csuir=1&mtid=UGihaZeLFN-fhbIP-OvDkQ4) to ensure visual consistency with the organisation’s identity.
- Downloaded ride category car images from [Pinterest](https://www.pinterest.com/pin/365776800991426694/) and used them to visually distinguish ride categories within the dashboard.
- Downloaded icons from [**Icons8**](https://icons8.com/icons) to improve usability and visual clarity.
- Downloaded star rating icons from [**EmojiCombos**](https://emojicombos.com/star-rating) and used them to represent customer and driver rating visuals in the report.

# Dashboards and Data Visualisation

**🔹 Data Visualisation**

- KPI cards summarising total bookings, completed trips, cancelled trips, total revenue generated, and average distance travelled (km).
- Card showing the ratio of completed trips and cancelled trips for each bolt category
- Bar charts highlighting revenue contribution by each bolt category.
- Area chart showing revenue trend by each month and year quarter.
- A doughnut chart displaying the distribution of payment methods for completed trips.
- KPI cards summarising the overall average ratings for both drivers and customers.
- A table chart showing a breakdown of pickup and drop-off locations, completed trips, and lost bookings by location.
- Table chart showing a summary of customer count, total bookings, completed and cancelled trips, total ride cost, distance travelled, and average driver and customer ratings across all ride categories.

# Insights

**🔹 How was Bolt's overall performance this year?**

This year, the numbers told a promising story; demand was strong. We recorded over **200,000** bookings on the Bolt platform, a clear sign that customers were choosing us. Out of those bookings, **119,885** trips were **completed**. About six in every ten bookings turned into actual rides. However, **70,196** trips were **cancelled**. Financially, the year closed well. Revenue reached approximately **₦1.59 billion**, and riders covered an average distance of **23.09 km** per trip.
However, beneath the growth sits an important question. If demand was clearly there, why were so many trips not completed? Reducing cancellations and investigating the reasons for the cancelled trips should be our main focus. If we can convert more of those bookings into completed trips, the impact on revenue and customer experience will be significant in the following year.

**🔹Which Bolt category generated the most revenue?**

Bolt Economy clearly dominated in revenue and outperformed other Bolt categories. **Bolt Economy** generated **₦871.91 million**, contributing **54.84%** of **total revenue**. This means more than half of the earnings came from Economy rides. The other categories followed behind. **Bolt XL** generated **₦314.53 million (19.84%)**, **Bolt Comfort ₦238.40 million (15.04%)**, and **Bolt Bike ₦160.19 million (10.11%)**. Strong numbers, but none close to Economy. It is not just about revenue. **Bolt Economy** also had the **highest bookings** and **completed trips**. This shows customers prioritise affordability first. (Price matters more than premium comfort or larger vehicle options).

The direction is clear. The focus needs to be shifted more to Bolt Economy by identifying common customer complaints, fixing service gaps, optimising our app, organising training and workshops for our drivers and regulating pricing to stay competitive. At the same time, we should review pricing across categories compared to other brands so we can attract more customers not just to Economy but to the other categories as well.

**🔹How did revenue trend across the months and year quarters?**

The year started strongly in **January** with revenue of **₦135.04 million**, then fell sharply in **February** to **₦119.70 million (-11.4%)**, the **lowest point of the year**. However, in **March** revenue increased to **₦135.02 million (+12.8%)**, closing **Q1** at **₦389.76 million, the lowest quarter**. By **April**, revenue slightly fell to **₦130.58 million (-3.3%);** by **May,** revenue increased to **₦135.13 million (+3.5%);** and by **June,** revenue slipped again to **₦129.69 million (-4.0%)**, bringing **Q2 to ₦395.41 million**. Momentum peaked in **July** at **₦136.96 million (+5.6%)**, the **highest month**, followed by **August** at **₦134.74 million (-1.6%)** and **September** at **₦130.93 million (-2.8%)**, making **Q3 the strongest quarter** at **₦402.62 million**. The year ended steadily: **October ₦133.61 million (+2.0%)**, **November ₦131.51 million (-1.6%)**, and **December ₦132.11 million (+0.5%)**, closing **Q4 at ₦397.24 million**.

Overall, the year was steady; after a sharp February drop, revenue moved in small rises and falls, peaking in Q3 and finishing the year stable without major seasonal demand fluctuations.

**🔹Which payment method did customers prefer?**

Customers clearly preferred digital payments, with **transfers** leading by a wide margin at **59,864 trips (49.93%)**, meaning almost half of all completed trips were paid directly from bank accounts. **Card** payments followed at **30,284 (25.26%)**, showing strong adoption for cashless options, while **cash** still accounted for **23,768 trips (19.83%).** While still relevant, cash is no longer the dominant method of payment. This shift reflects Nigeria’s growing cashless culture, where many customers now prefer transfers and POS-based transactions over physical cash. **Bolt Balance** was used the least at **5,969 (4.98%)**, suggesting that only a small group relies on it for in-app stored funds.

In summary, our customers preferred fast, seamless digital payments, with transfers emerging as the default way to pay for rides and services.

**🔹How were customers’ and drivers’ satisfaction levels?**

When we look at our **customers**’ and **drivers**’ feedback, the story is steady and reassuring. Both groups recorded an average rating of **4.00**. This tells us the overall experience was positive between drivers and customers, service delivery was consistent, expectations were largely being met, and there were no clear signs of widespread dissatisfaction. What was most interesting was the stability of these ratings across all ride categories. Whether it was Economy, XL, Comfort, or Bike, the experience remained largely the same and positive. This level of consistency shows operational standards are being maintained between drivers and customers.
However, the focus should be on how we can improve the 4.00 baseline by improving service quality, responsiveness, or customer care, which could push satisfaction higher, increase revenue and customers numbers. 

**🔹How did completed trips compare to cancellations?**

**Completed trips** were higher than **cancellations**, which is encouraging. However, cancellations was noticeable high. For example, looking at high-traffic routes such as Ajah → Ikeja and Mile2 → Lekki, completed trips averaged between 1,100 and 1,300, while lost bookings ranged from 650 to 740. This clearly indicates strong demand, but supply was not consistently meeting that demand during peak hours. It may also suggest that some customers were switching to competitors offering better pricing or faster availability.

To close this gap, I suggest we implement more targeted and strategic advertisements for drivers to register under Bolt by offering a more competitive commission percentage compared to our competitors, which could attract more drivers to register and stay active on the platform. At the same time, reviewing and regulating trip pricing will ensure we remain competitive in the market, reward drivers and customers who have been with us for a long time. which will help strengthen driver supply, especially during peak periods, reduce unavailability and ultimately lower cancellations.

**🔹What patterns emerge across our ride categories?**

**Bolt Economy** stands out as the backbone of our transport service. It led in customers, bookings, revenue, and total distance travelled. Bolt Economy is the engine that keeps the business moving, driven by affordability and mass demand. **Bolt XL** tells a different story. While it recorded fewer trips, it still generated strong revenue. This suggests higher fares per ride, making it the preferred option for group travel and customers willing to pay more for space. **Bolt Comfort** sits in the middle. It showed steady and moderate performance across all metrics, serving customers who want a balance between price and experience. **Bolt Bike** generated the lowest revenue among the categories, yet its contribution remained meaningful. Its usage pattern suggests strong relevance for short trips and deliveries, especially in areas where speed and cost efficiency matter most.
Together, these categories show a layered demand structure, with Economy driving volume, XL driving higher ticket value, Comfort offering balance, and Bike serving niche but important mobility needs.

# Recommendations

**🔹 Reduce cancellations**

Demand is already strong, but too many bookings are lost before completion.

What to do:

- Recruit more drivers in high-demand areas (Ajah, Lekki, Ikeja, Mile 2 corridors)
- Introduce peak-hour driver incentives
- Improve driver allocation to reduce pickup time
- Penalise frequent driver cancellations and reward reliability

**🔹Double down on Bolt Economy**

Economy generates over half of total revenue and drives most usage

What to do:

- Keep Economy pricing competitive
- Improve wait times for Economy rides
- Offer loyalty rewards for frequent Economy users
- Fix common complaints

**🔹Strengthen driver supply and retention**

Supply shortages are driving cancellations

**What to do:**

- Offer better commission structure for top drivers
- Provide fuel or maintenance partnerships/discounts
- Create driver bonus programs for peak-hour availability
- Improve driver support and communication

**🔹Optimise pricing strategy**

Customers are price-sensitive, but premium categories are underutilized.

**What to do:**

- Use dynamic pricing carefully to avoid pushing users to competitors
- Offer targeted discounts during low-demand periods
- Bundle promotions (e.g., weekend Comfort discounts)

**🔹Improve customer experience to push ratings above 4.0**

A 4.00 rating is good but not exceptional.

**What to do:**

- Introduce driver training on professionalism and safety
- Improve in-app support response time
- Reward highly rated drivers and riders
- Introduce service quality monitoring

**🔹Grow underperforming categories strategically**

Each category serves a different need.

**Opportunities:**

- **XL:** Target airports, events, group travel
- **Comfort:** Market to business users
- **Bike:** Expand for short-distance trips and deliveries

# Summary

The year showed strong and steady performance for Bolt, driven by high customer demand and consistent revenue throughout the months. Bolt Economy remained the backbone of our transport service, which showed that most of our customers prioritise affordability, while other categories supported with smaller but important contributions. Customer and driver satisfaction stayed positive, and digital payments became our customers’ most preferred payment method. 

However, the year was also defined by a major challenge: high cancellations, which prevented a large portion of bookings from becoming completed trips. This indicates that while demand was never the problem, supply and availability were. In summary, it was a year of solid growth and stability, with the biggest opportunity lying in converting strong demand into more completed rides next year.

**🔹 Tools and Technologies**
- Power BI
- Excel
- Github
