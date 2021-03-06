# Jungle

A mini e-commerce application built with Rails 4.2 and Stripe. PostgreSQL used as a database. Users can see their detailed order after the purchase and also receive a receipt via email. As a user, you can leave product review and rating for other people to see. Admins are able to create new product categories and add items to the store.

## Setup

1. Fork & Clone
2. Run `bundle install` to install dependencies
3. Create `config/database.yml` by copying `config/database.example.yml`
4. Create `config/secrets.yml` by copying `config/secrets.example.yml`
5. Run `bin/rake db:reset` to create, load and seed db
6. Create .env file based on .env.example
7. Sign up for a Stripe account
8. Put Stripe (test) keys into appropriate .env vars
9. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

* Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
* PostgreSQL 9.x
* Stripe

## Screenshots

!["This is JungleApp home page"](docs/Main_Page.png)
!["This is an admin page to add new items or product categories to the store"](docs/Admin_Page.png)
!["This is the page that show the details of your order"](docs/Order_Page.png)
!["This a product page where signed users can post their reviews."](docs/Product_page.png)
