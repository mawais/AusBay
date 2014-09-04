AusBay.com is free  bidding web site . It works same as ebay. But not in advance. The aim of this simple website to add items for bid or sale or buy item from there..i am going to opensource all of my code for free to use and improve it or modify it if you think .

....................................................................................
About  ausbay.com


Modified specification to put "add new item" form on home page to fill page
and avoid an unnecessary link.
Extended specification to make category a link on "item details" page.
After deleting an item, displays list of items in category of deleted item.
Validates that item name, category, vendor and price are nonempty,
and that price is a positive number.  Description may be empty.
Trims search terms.
Santises all user input (but does not restrict length).
The implementation sometimes uses $item (resp., $category) as an object
and sometimes as the id of that object.  Be careful.
Although the specification does not require this, the interface would be
improved if there were a navigation element to search for items and add
a new item on every page.
This is all the documentation there is.
