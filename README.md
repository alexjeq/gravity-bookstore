# Bookstore

Here’s the ERD of the sample bookstore database we’ll be looking at.

![erd_gravity-2048x1163](https://github.com/alexjeq/gravity-bookstore/assets/74671209/06eb1a91-9e55-433a-a4bf-6c3e0a85a95d)

This contains the following tables:
* **book**: a list of all books available in the store.
* **book_author**: stores the authors for each book, which is a many-to-many relationship.
* **author**: a list of all authors.
* **book_language**: a list of possible languages of books.
* **publisher**: a list of publishers for books.
* **customer**: a list of the customers of the Gravity Bookstore.
* **customer_address**: a list of addresses for customers, as a customer can have more than one address, and an address has more than one customer.
* **address_status**: a list of statuses for an address, because addresses can be current or old.
* **address**: a list of addresses in the system.
* **country**: a list of countries that addresses are in.
* **cust_order**: a list of orders placed by customers.
* **order_line**: a list of books that are a part of each order.
* **shipping_method**: the possible shipping methods for an order.
* **order_history**: the history of an order, such as ordered, cancelled, delivered.
* **order_status**: the possible statuses of an order.
0 comments on commit c667b22
@alexjeq
Comment
 
Leave a comment
 
Footer
© 2024 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact
Manage cookies
Do not share my personal information
