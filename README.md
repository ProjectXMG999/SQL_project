## SQL_project

NOTE!
- will need to replace stripe_publishable_key and stripe_secret_key with your own Stripe API keys.


Design the database schema:
- Products: product_id, name, description, price, category_id, image_url
- Categories: category_id, name
- Customers: customer_id, name, email, address, phone
- Orders: order_id, customer_id, total_price, date
- Order_items: order_id, product_id, quantity, price
- Payments: payment_id, order_id, payment_method, amount, date
