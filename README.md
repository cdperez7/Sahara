![s1](https://i.imgur.com/XJCbx4J.png)

## Sahara

This was the second group project as part of my Northwestern Coding Bootcamp course. Sahara is an online store and marketplace for users to buy and sell products. Users can create an account, and either put their own products up for sale or purchase products entered by other users. All information is stored in a MySQL database and updated automatically as the sellers/buyers use the site (after items are bought, quantity goes down, new products to be sold are added to database, etc.). Users can also update their own items (price, quantity, etc.) as well as delete their postings. Both a history of bought and sold items is also stored for the buyers/sellers to view.

Users can use the main search bar to find any product that is pulled based on their search term. They can also view all items in a certain category if they are unsure what they want to buy. Login account information is stored using express-session package. 

## Front End

![s2](https://i.imgur.com/Ae8UdGO.png)

We aimed for a clean, simple design, with each product located in their own div. Based on our company name, we went with a light yellow/desert style. The following image shows what happens when a user searched "cat".

















## Future Optimization
* Building a full database to store more products as a real online store would have
* Support/chat function for customer support
* Purchase multiple quantities of an item
* Account deletion feature
* Adding more categories and allowing users to create a new category that does not exist
* Store images as a file and not a link in the database
