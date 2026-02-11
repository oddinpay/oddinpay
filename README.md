> [!WARNING]  
> ## 🚧 Work in Progress
> This project is currently under active development.  

# oddinpay

🛍️ Easy to use full featured API & SDKs for oddin payments, shipping and online store.

## Example

```ts
import { createPayment } from "@oddinpay/oddinpay";

const checkoutLink = await createPayment({
  amount: 1000,
  currency: "USD",
});

console.log(checkoutLink);
```
