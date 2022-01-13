# Event Booking Completed

### 

## Javascript Code
```js
window.dataLayer09876 = window.dataLayer09876 || [];
dataLayer09876.push({ ecommerce: null });  // Clear the previous ecommerce object.;;
dataLayer09876.push({
  "event": "purchase",
  "apollo_event": "Event Booking Completed",
    "ecommerce": {
        "booking_reservation_id": "<booking_reservation_id>",
        "currency": "<currency>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "transaction_id": "<transaction_id>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|booking_reservation_id|string|Captures the reservation ID associated with each booking.||^[a-zA-Z0-9]{6,20}$|6|20||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||




