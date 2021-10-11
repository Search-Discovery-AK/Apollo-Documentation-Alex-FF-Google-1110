# Product Viewed

### 

## Javascript Code
```js
window.dataLayer1110 = window.dataLayer1110 || [];
dataLayer1110.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer1110.push({
  "event": "Product Viewed",
    "items": [
        {
            "affiliation": "<affiliation>",
            "discount": "<discount>",
            "item_brand": "<item_brand>",
            "item_id": "<item_id>",
            "item_name": "<item_name>",
            "price": "<price>"
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||




