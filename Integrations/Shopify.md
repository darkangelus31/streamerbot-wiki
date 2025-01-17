---
title: Shopify
description: If you can dream it, you can sell it with Shopify
published: false
date: 2022-11-15T15:23:48.146Z
tags: v0.1.14
editor: markdown
dateCreated: 2022-11-14T23:05:03.709Z
---

## Variables
### Order Created
Name | Description
----:|:------------
`shopify.created_at` | 11/15/2022 12:21:46 AM
`shopify.event` | orders/create
`shopify.id` | 820982911946154500
`shopify.email` | jon@doe.ca
`shopify.closed_at` | 
`shopify.updated_at` | 11/15/2022 12:21:46 AM
`shopify.number` | 234
`shopify.note` | 
`shopify.total_price` | 254.98
`shopify.subtotal_price` | 244.98
`shopify.currency` | EUR
`shopify.financial_status` | voided
`shopify.confirmed` | False
`shopify.total_discounts` | 5.00
`shopify.total_line_items_price` | 249.98
`shopify.buyer_accepts_marketing` | True
`shopify.name` | #9999
`shopify.referring_site` | 
`shopify.landing_site` | 
`shopify.total_price_usd` | 
`shopify.order_number` | 1234
`shopify.line_items[#].id` | 487817672276298560
`shopify.line_items[#].variant_id` | 
`shopify.line_items[#].title` | Aviator sunglasses
`shopify.line_items[#].quantity` | 1
`shopify.line_items[#].sku` | SKU2006-001
`shopify.line_items[#].variant_title` | 
`shopify.line_items[#].vendor` | 
`shopify.line_items[#].fulfillment_service` | manual
`shopify.line_items[#].product_id` | 788032119674292900
`shopify.line_items[#].requires_shipping` | True
`shopify.line_items[#].taxable` | True
`shopify.line_items[#].gift_card` | False
`shopify.line_items[#].name` | Aviator sunglasses
`shopify.line_items[#].variant_inventory_management` | 
`shopify.line_items[#].product_exists` | True
`shopify.line_items[#].fulfillable_quantity` | 1
`shopify.line_items[#].grams` | 100
`shopify.line_items[#].price` | 89.99
`shopify.line_items[#].total_discount` | 0.00
`shopify.line_items[#].fulfillment_status` | 
`shopify.line_items[#].price_set.shop_money.amount` | 89.99
`shopify.line_items[#].price_set.shop_money.currency_code` | EUR
`shopify.line_items[#].price_set.presentment_money.amount` | 89.99
`shopify.line_items[#].price_set.presentment_money.currency_code` | EUR
`shopify.line_items[#].total_discount_set.shop_money.amount` | 0.00
`shopify.line_items[#].total_discount_set.shop_money.currency_code` | EUR
`shopify.line_items[#].total_discount_set.presentment_money.amount` | 0.00
`shopify.line_items[#].total_discount_set.presentment_money.currency_code` | EUR
`shopify.line_items[#].admin_graphql_api_id` | gid://shopify/LineItem/487817672276298554
`_json` | These variables in JSON for C# usage.
`actionId` | 673dbf96-b118-4601-85f5-78045910db51
`eventSource` | shopify
`runningActionId` | 4a7b8da0-622b-4903-8df8-28bc8f276932

### Order Paid
Name | Description
----:|:------------
`shopify.created_at`| The time the order was paid.
`shopify.event` | orders/paid
`shopify.id` | The shopify id.
`shopify.email` | The email of the customer e.g. `jon@doe.ca`.
`shopify.closed_at` |
`shopify.updated_at` |
`shopify.number` | 234
`shopify.note` | 
`shopify.total_price` | 254.98
`shopify.subtotal_price` | 244.98
`shopify.currency` | The 3 letter currency e.g. `EUR`.
`shopify.financial_status` | voided
`shopify.confirmed` | The confirmed status `True`/`False`.
`shopify.total_discounts` | The total amount of discount e.g. `5.00`.
`shopify.total_line_items_price` | The total price e.g. `249.98`.
`shopify.buyer_accepts_marketing` | If the customer accepts marketing `True`/`False`.
`shopify.name` | #9999
`shopify.referring_site` | 
`shopify.landing_site` | 
`shopify.total_price_usd` | 
`shopify.order_number` | The order number.
`shopify.line_items[#].id` | The item id.
`shopify.line_items[#].variant_id` | The item variant id.
`shopify.line_items[#].title` | The item's title e.g. `Aviator sunglasses`.
`shopify.line_items[#].quantity` | The quantity of this item.
`shopify.line_items[#].sku` | The stock keeping unit e.g. `SKU2006-001`.
`shopify.line_items[#].variant_title` | The item variant title.
`shopify.line_items[#].vendor` | The seller of this item.
`shopify.line_items[#].fulfillment_service` | The fulfillment service e.g. `manual`.
`shopify.line_items[#].product_id` | The product's id of this item.
`shopify.line_items[#].requires_shipping` | If this item requires shipping `True`/`False`.
`shopify.line_items[#].taxable` | If this item is taxable `True`/`False`.
`shopify.line_items[#].gift_card` | If this item is a gift card.
`shopify.line_items[#].name` | The item's name e.g. `Aviator sunglasses`.
`shopify.line_items[#].variant_inventory_management` | 
`shopify.line_items[#].product_exists` | If the products exist `True`/`False`.
`shopify.line_items[#].fulfillable_quantity` | The quantity left of this item.
`shopify.line_items[#].grams` | The amount of metric grams in this item e.g. `100`.
`shopify.line_items[#].price` | The price of this item e.g. `89.99`.
`shopify.line_items[#].total_discount` | The total discount on this item e.g. `0.00`.
`shopify.line_items[#].fulfillment_status` | The fulfillment status of this item.
`shopify.line_items[#].price_set.shop_money.amount` | 89.99
`shopify.line_items[#].price_set.shop_money.currency_code` | EUR
`shopify.line_items[#].price_set.presentment_money.amount` | 89.99
`shopify.line_items[#].price_set.presentment_money.currency_code` | EUR
`shopify.line_items[#].total_discount_set.shop_money.amount` | 0.00
`shopify.line_items[#].total_discount_set.shop_money.currency_code` | EUR
`shopify.line_items[#].total_discount_set.presentment_money.amount` | 0.00
`shopify.line_items[#].total_discount_set.presentment_money.currency_code` | EUR
`shopify.line_items[#].admin_graphql_api_id` | gid://shopify/LineItem/487817672276298554
`_json` | These variables in JSON for C# usage.