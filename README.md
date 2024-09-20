


Data generator posts product-related events:

* View
* Cart
* Uncart
* Purchase
* Return

An example `view` event: 

```json
{
    "customer_id": "customer_464",
    "product": {
        "product_id": "product_17"
    },
    "action": "view",
    "timestamp": "2024-09-19T16:33:11"
}
```

An example `purchase` event. These events add a `price` attribute: 

```json
{
    "customer_id": "customer_27",
    "product": {
        "product_id": "product_499",
        "price": 23.99
    },
    "action": "purchase",
    "timestamp": "2024-09-19T16:31:13"
}
```