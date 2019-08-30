# Class: HouseListing

## Attributes:

1. square_feet (integer)
2. premium_discount_multiplier (float)
3. owner (string)
4. for_sale (boolean)
5. base_price (integer)

## Methods:

1. update_premium_discount_multiplier
    - Action: update `premium_discount_multiplier` to reflect new premium or discount
    - Attribute(s) used: `prem_discount_multiplier`
2. display_list_price
    - Action: `print "list price: #{base_price * prem_discount_multiplier}"`
    - Attribute(s) used: `list_price` and `prem_discount_multiplier`
3. ownership_changed
    - Action: change name of `owner` to new string
    - Attribute(s) used: `owner`
4. sold
    - Action: change `for_sale` from true to false
    - Attribute(s) used: `for_sale`
