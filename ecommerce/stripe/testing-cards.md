Test Credit Card Numbers for eCommerce

| Merchant      | Type			| Card Number			| Expected Response			|
| ------------- | ------------- | --------------------- | -------------------------	|
| Stripe		| Visa			| 4242 4242 4242 4242	| Approved					|
| Stripe		| Mastercard	| 5555 5555 5555 4444 	| Approved					|
| Stripe		| Visa			| 4000 0000 0000 0002 	| Declined (No funds)		|
| Stripe		| Visa			| 4242 4242 4242 4241 	| Declined (Invalid CV2)	|



