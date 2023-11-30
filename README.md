This repo contains my deck submission for a Senior Operations Analyst role final round case study in both PDF and powerpoint formats.

I analyzed metrics relating to the operations of a grocery delivery platform and **found that the speed at which shoppers accept an order from a customer has the greatest impact on the on-time delivery of an order**. This insight led me to recommend creating strategies to incentivize shoppers to accept an order more quickly, such as a higher pay rate or bonus pay when an order is accepted within x number of minutes. 

The provided Excel file contains information relating to one weeks worth of orders in one market:

**Orders:**

Order ID: Unique identifier of the order.

Shopper ID: Unique identifier of the shopper.

Store ID: Unique identifier of the store.\

Branch ID: Unique identifier for each branch of the store. For example, XYZ store (store ID) has 10 different branches in the marketplace, all with a different branch ID.

On demand? (Yes/No): : If the order was requested to be delivered right away (Yes) or in a future time window (No).

Total Picking Assigning Time: How long it takes before an order is accepted by a shopper.

Setup Distance (KM.): Distance from the shopper initial location to the store

Qty Products Ordered: Total number of items ordered by the customer in the order.

Day of the Week: Day of the week of the order delivery

Order Punctuality: Indicates if the order was delivered early, on time or later than expected.

Detailed Punctuality Tier: Breakdown of the earliness/lateness of the delivery



**Shoppers:**

Shopper ID: Unique identifier of the shopper.

Completed Pickings Tier: Tier of the number of orders completed by the shopper (over included,
under excluded)

Found Rate: Average percentage of the exact products that the shopper found as requested by the
customer (sum of products found/sum of products requested)

Picking Speed: Average speed of picking each product (average time spent shopping/number of
products found and replaced)

Picking Acceptance Rate: Average rate of orders accepted by the shopper

Rating: Average rating given to the Shopper by the Customer.
