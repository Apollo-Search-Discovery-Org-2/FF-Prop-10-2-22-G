# Internal Campaign Clicked

### 

## Javascript Code
```js
window.dataLayer000 = window.dataLayer000 || [];
dataLayer000.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer000.push({
  "event": "Internal Campaign Clicked",
    "ecommerce": {
        "creative_name": "<creative_name>",
        "creative_slot": "<creative_slot>",
        "internal_campaign_creative": "<internal_campaign_creative>",
        "internal_campaign_id": "<internal_campaign_id>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "location_id": "<location_id>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|creative_name|string|The name of the promotional creative.||||||||
|creative_slot|string|The name of the promotional creative slot associated with the event.||||||||
|internal_campaign_creative|string|Count of impressions for external campaigns taking place outside of the website \(i.e. Google Ads, Doubleclick display ads\).|Girl with bike, Mountain Top, River Cruise Danube|||||||
|internal_campaign_id|string|Captures the URL of the exit link.|2345, 56789, 9876|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||




