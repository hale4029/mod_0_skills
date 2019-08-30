# Instance: listing_1010

## Attributes:

1. square_feet = 2,000
2. premium_discount_multiplier = 1.10
    - this would indicate a 10% premium from base_price
3. owner = "Harrison Levin"
4. for_sale = True
5. base_price = $200,000

## Methods:

1. update_premium_discount_multiplier
    - **Output: change from 1.00 to 1.10**
    - Action: update `prem_discount_multiplier` to reflect new premium or discount
    - Attribute(s) used: `prem_discount_multiplier`
2. display_list_price
    - **Output: $220,000**
    - Action: `print "list price: #{base_price * prem_discount_multiplier}"`
    - Attributes used: `list_price` and `prem_discount_multiplier`
3. ownership_changed
    - **Output: change name to "Ellyn Green"**
    - Action: change name of `owner` to new string
    - Attributes used: `owner`
4. sold
   - **Output: change from True to False**
   - Action: change `for_sale` from true to false
   - Attribute(s) used: `for_sale`
