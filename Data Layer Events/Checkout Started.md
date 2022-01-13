# Checkout Started

### 

## Javascript Code
```js
window.dataLayer09876 = window.dataLayer09876 || [];
dataLayer09876.push({ ecommerce: null });  // Clear the previous ecommerce object.;;
dataLayer09876.push({
  "event": "begin_checkout",
  "apollo_event": "Checkout Started",
    "ecommerce": {
        "currency": "<currency>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "product_sku": "<product_sku>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|product_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||




