# Smart India Hackathon Workshop
# Date: 27-10-2026
## Reference Number: 26008637
## Name: MADHUSHRI T

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a transparent digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Compares selling options based on estimated net earnings after expenses.
• Displays transparent cost breakdowns and supports shared transportation planning.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
### FairShare Market – NetEarning Compare

FairShare Market is a digital agricultural platform designed to help farmers compare different selling options and understand how much money they may actually earn from their crops.

The main feature, **NetEarning Compare**, calculates the estimated amount a farmer receives after accounting for transportation, handling charges, commissions, and other selling expenses.

Farmers enter their crop details, quantity, expected selling price, and location. Buyers can provide their required quantities, preferred prices, and delivery locations. The platform compares suitable selling options and displays the estimated earnings associated with each option.

The system can also group compatible orders from nearby buyers to estimate shared transportation costs. This helps farmers evaluate whether a combined delivery could be more economical than separate deliveries.

### How It Addresses the Problem

1. Helps farmers compare selling options instead of depending on a single intermediary.
2. Displays estimated deductions and net earnings transparently.
3. Helps consumers understand the components contributing to the final price.
4. Estimates potential transportation savings through grouped orders.
5. Connects participating farmers and buyers through a digital marketplace.

### Innovation and Uniqueness

The main feature of FairShare Market is its NetEarning Compare system, which focuses on the amount farmers may actually receive rather than displaying selling prices alone.

For example, two buyers may offer different prices for the same crop, but transportation and handling costs may affect which option is more profitable for the farmer.

FairShare Market compares the estimated net earnings from suitable options and explains the cost differences. Farmers can then make informed decisions before accepting an order.

The platform combines transparent cost breakdowns, selling-option comparisons, and shared delivery estimates to support fairer agricultural trading.

## Technical Approach

1. Frontend: HTML, CSS, and JavaScript for the user interface.
2. Backend: Python with Flask for application logic and calculations.
3. Database: SQLite for storing farmer details, crop listings, buyer offers, and transportation costs.
4. Cost Comparison Engine: Python functions to calculate estimated net earnings for different selling options.
5. Mapping: OpenStreetMap-based tools to estimate distances and identify possible shared delivery routes.

### Methodology and Implementation

1. Farmers register and enter crop details, quantities, locations, and expected selling prices.
2. Buyers submit offers containing the required crop, quantity, offered price, and delivery location.
3. The system identifies suitable selling options based on crop type, quantity, and location.
4. The NetEarning Compare engine calculates the estimated net earnings for each suitable option.
5. The system compares transportation, handling, commission, and other applicable costs.
6. Compatible orders are grouped to estimate possible savings from shared transportation.
7. The platform displays a comparison report showing the offered price, estimated expenses, and estimated net earnings.
8. Farmers review the results and decide whether to accept an offer.

### Net Earnings Calculation

Estimated Net Earnings = Gross Selling Revenue − Total Estimated Selling Costs

Estimated Selling Costs may include transportation, handling, commissions, packaging, and other applicable charges.

The system will clearly distinguish estimated costs from confirmed costs. Farmers will make the final selling decision.

### Technical Approach Flowchart

```text
       +-----------------------+
       | Farmer and Buyer      |
       | Registration          |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Enter Crop Details,   |
       | Prices and Locations  |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Identify Suitable     |
       | Buyer Offers          |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Calculate Estimated   |
       | Selling Costs         |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | NetEarning Compare    |
       | Calculates Earnings   |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Compare Selling       |
       | Options               |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Estimate Shared       |
       | Transport Savings     |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Display Comparison    |
       | Report                |
       +-----------------------+
                  |
                  v
       +-----------------------+
       | Farmer Chooses a      |
       | Suitable Offer        |
       +-----------------------+
```

### Prototype Development

The initial prototype will include farmer registration, crop listings, buyer offers, cost entry, net earnings calculations, and a comparison dashboard.

The calculation engine will initially use user-provided prices and expenses. The shared transportation feature will estimate potential savings using order locations and delivery requirements.

The prototype will be tested using sample crop transactions to check calculation accuracy, comparison results, and ease of use.

## Feasibility and Viability
### Feasibility of the Idea

FairShare Market can be developed as a web application using HTML, CSS, JavaScript, Python, Flask, and SQLite.

The initial prototype requires only basic farmer records, buyer offers, and selling-cost information. The NetEarning Compare feature can be implemented using straightforward mathematical calculations.

A more advanced version can incorporate location-based delivery estimates and order grouping.

### Potential Challenges and Risks

1. Farmers may not know the exact transportation and handling costs in advance.
2. Buyer offers and crop prices may change over time.
3. Incomplete cost information may produce inaccurate comparisons.
4. Farmers may have limited internet access or digital experience.
5. Estimated transportation savings may differ from actual savings.

### Strategies to Overcome the Challenges

1. Allow farmers to enter their own expenses and update them when necessary.
2. Display the date and source of price information wherever available.
3. Show the assumptions used in each earnings calculation.
4. Provide a simple interface with clear instructions and local-language support.
5. Label all calculated earnings and delivery savings as estimates until actual costs are confirmed.

## Impact and Benefits
### Impact on the Target Audience

FairShare Market is designed to benefit farmers, Farmer Producer Organizations, retailers, bulk buyers, and consumers.

Farmers can compare selling options and understand the expenses affecting their earnings. Buyers can review crop offers and better understand the costs involved in supplying agricultural produce.

### Economic Benefits

- Better visibility of farmers' estimated net earnings.
- Improved ability to compare different buyer offers.
- Potential savings through shared transportation.
- Greater transparency in selling costs and price differences.

### Social Benefits

- Helps farmers make informed selling decisions.
- Encourages transparent communication between farmers and buyers.
- Supports small farmers who may have limited access to market information.

### Environmental Benefits

- Potential reduction in unnecessary delivery trips through order grouping.
- More efficient transportation planning.
- Potential reduction in food waste when improved market coordination helps produce reach buyers.

The actual impact will depend on participation, the accuracy of cost information, buyer availability, and transportation conditions.

## Research and References

1. e-NAM (National Agriculture Market): Reference for electronic agricultural trading and market connectivity.
2. AGMARKNET: Reference for agricultural commodity market prices and market information.
3. Ministry of Agriculture and Farmers Welfare, Government of India: Reference for agricultural policies and farmer-related initiatives.
4. OpenStreetMap: Reference for geographical information and potential delivery-route planning.

### Application of Research

Agricultural market information can help inform the platform's price comparison features. Location information can support the estimation of delivery distances and possible shared transportation arrangements.

The NetEarning Compare feature will be implemented as part of the proposed prototype and tested using sample crop transactions and selling expenses.
