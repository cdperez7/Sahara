![s1](https://i.imgur.com/XJCbx4J.png)

## Sahara

Heroku link for Sahara: https://sahara-marketplace.herokuapp.com/

This was the second group project as part of my Northwestern Coding Bootcamp course. Sahara is an online store and marketplace for users to buy and sell products. Users can create an account, and either put their own products up for sale or purchase products entered by other users. All information is stored in a MySQL database and updated automatically as the sellers/buyers use the site (after items are bought, quantity goes down, new products to be sold are added to database, etc.). Users can also update their own items (price, quantity, etc.) as well as delete their postings. Both a history of bought and sold items is also stored for the buyers/sellers to view.

Users can use the main search bar to find any product that is pulled based on their search term. They can also view all items in a certain category if they are unsure what they want to buy. Login account information is stored using express-session package. We created our own Sahara specific ORM for this website instead of using Sequelize.

## Front End

![s2](https://i.imgur.com/Ae8UdGO.png)

We aimed for a clean, simple design, with each product located in their own div. Based on our company name, we went with a light yellow/desert style. We used express/handlebars to create all pages. The following image shows what happens when a user searched "cat". You can see that the page displays products with the search term in either the title or anywhere in the description.

![s3](https://i.imgur.com/HeZB5Sr.png)

The following images are just to give a viewer a sense of how everything updates on our website. After creating an account, I added a new item (rubber duck) for sale and entered in the price/quantity/etc. 

![s4](https://i.imgur.com/r37PDmB.png)

![s5](https://i.imgur.com/KWwZdBd.png)

You can see how it is then displayed as a new product on our website. After adding, it is displayed in my accounts "items for sale" page. 

![s6](https://i.imgur.com/Ov8k7q0.png)

![s7](https://i.imgur.com/v56gKtn.png)


After this, I went and purchased two items, one rubber duck and The Lord of the Rings - Return of the King. You can see how these are displayed in my purchase history. Also note that the quantity of Rubber Duck's changed from 50 to 49 after I purchased one.

![s8](https://i.imgur.com/8ui7JaM.png)

![s9](https://i.imgur.com/TOZKjR9.png)


Hopefully these images and descriptions give you a good idea of how the site works and looks. Of course feel free to play with it yourself via the above Heroku deployed link.


## Technologies Used
* HTML
* CSS
* Express
* Handlebars
* MySQL
* Node.js
* Javascript
* jQuery



## Future Optimization
* Building a full database to store more products as a real online store would have
* Support/chat function for customer support
* Purchase multiple quantities of an item
* Account deletion feature
* Adding more categories and allowing users to create a new category that does not exist
* Store images as a file and not a link in the database
