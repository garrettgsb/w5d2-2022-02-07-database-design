# Entities

* Users
  * name
  * email
  * admin? true/false
* Products
  * rating
  * quantity
  * quality
* Images
* Admins
* Ratings
* Orders
* Comments
* Stores
* Videos
* Notifications
* Cart
* Questions
* Answers
* Movies/Shows (Productions?)
* Chatrooms/Chats
* Support Tickets
* Policies
* Discount/Promo Code
* Rooms
* Subscriptions
* Entries (e.g. in a Dictionary)
* Dictionaries
* Sessions
* Roles


# Quick E-Commerce Lesson

* Products
  * quantity?
  * price $6.50
* Cart
* Orders
* Line Items
  * which product is it?
  * how many do they want?
  * what will they pay for it?
  * actual price at time of purchase: $5.85


# E-Commerce Site Example

* Products
  * id
  * price
  * stock
  * description
  * aisle
  * colours
  * category
  * size
  * vendor/source
  * discount
  * item number/serial number/SKU
  * low_stock_threshold
  * created_at
  * updated_at
  * deleted_at
  * (derived) average_rating

* Comments
  * id
  * user_id
  * product_id
  * helpful_count
  * unhelpful_count
  * rating
  * is_verified
  * created_at
  * content (body, text)

* Questions
  * id
  * user_id
  * product_id
  * content
  * created_at
  * type (technical, vendor, shipping)
  * (derived) is_answered
* Answers
  * id
  * user_id
  * question_id
  * content
  * created_at
  * helpful_count
  * unhelpful_count


* Images
* Users
* Orders
* Line Items
* Shipping Details
* Promo Code
