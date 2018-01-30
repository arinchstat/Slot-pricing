# Slot-pricing
This model is build with the aim to increase delivery revenue using an optimization technique that suggets altering prices based on their sensitivity and opportunity.

The code creates assembly of functions which are interdependent (output of one feeds into another). The flow is to extract the data from XXX database that stores the order details (order data, shopping value, delivery fee paid, slot chosen, serving store id, etc.) and then fire the functions one by one that generates the required data one by one.

The ultimate function to generate the recommended grids is the getPriceRecommendations function. The benchmarkPricesAgainstControl function generates the performance dashboard.
