# Methods
* `getOrder(tableNum)`

Given a table number returns the order as a record.

* `submitOrder(order)`

Given a javascript object, will send it to the main database

* `editOrder(tableNum, item, change)`

Given a table number and item to change, will change the item to change

* `markOrderMade(tableNum)`

Given a table number, will mark the order as made to notify floor staff

* `markDishMade(tableNum, dish)`

Given a table number and a dish in the order, will mark the dish as made to notify floor staff

* `markOrderPaid(tableNum)`

Given a table number, will mark the order as finished and will store the data in a database

* `getDishes()`

Returns javascript object of all dishes in database

* `addDish(name, price, description)`

Given the name, price and description of a dish, will add it to the database

* `changeDish(name, element, change)`

Given the name and element of a dish, will change the value of element to change

