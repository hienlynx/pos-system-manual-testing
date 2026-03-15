| Transaction        | Actor                     | Entities Affected      |
| ------------------ | ------------------------- | ---------------------- |
| Add Item to Cart   | Cashier                   | Cart, Product          |
| Checkout           | Cashier                   | Cart, Sale Transaction |
| Process Payment    | Cashier / Payment Gateway | Payment                |
| Generate Receipt   | POS System                | Receipt                |
| Refund Transaction | Cashier                   | Payment, Inventory     |
| Update Inventory   | POS System                | Inventory              |
