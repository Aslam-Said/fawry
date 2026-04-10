# fawry
Shippable                   → Interface required by ShippingService
Product                     → Base class for all products
ExpirableProduct            → Products that can expire (e.g. Milk)
ShippableProduct            → Products that need shipping (e.g. TV)
ExpirableShippableProduct   → Both expire and need shipping (e.g. Cheese, Biscuits)
CartItem                    → Holds a product + quantity pair
Cart                        → Manages the customer's selected items
Customer                    → Has a name and a balance
ShippingService             → Prints shipment notice and calculates shipping fees
CheckoutService             → Handles the full checkout flow
FawryEcommerce              → Main class with all test cases
