# Pricing-Model
Implement an everyday-low-price (EDLP) strategy for 10 products to improve revenue of ACSE supermarket. To offset the costs of this strategy, increase the price of 50 products that are less price-sensitive and have stable demand.

To increase overall revenue by adjusting product shelf prices,firstly calculate the elasticity(sensitivity) of products with high demand. Then, build a pricing model to predict product demand, exploring the relationship between price and demand. Finally, optimize the price of each product based on revenue and elasticity for each store and overall across all stores.

# Elasticity
Calculate product elasticity with Constant-E model. 

log(Demand) ~ elasticity * log(Price)

# Demand-Price
The dependent features include product price, competitor price, complementary price, substitute price and seasonality index. 

# EDLP - Everyday Low Price Retailer
EDLP strategy takes into account competitor prices and the logit response scenario to calculate the optimal price.

