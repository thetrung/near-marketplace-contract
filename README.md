# near-marketplace-contract
Contract written on progress with dacode tutorials.

### Note
It consist of 3 structs : product, payload and marketplace.

- `Product` : contain product information, including owner and sales counting.

- `Payload` : receive input from contract caller to setup product data.

- `Marketplace` : to process list, create, update, buy product functions.

* `buy_product` will involve process of `Promise(..).transfer`, `increment_sold_amount` and `listed_products.insert` (to update sale counting).
