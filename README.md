# Ship-Station-Database

This is a shipping company named Ship Station.
Ship Station helps other companies/businesses in South-Africa to import products from all over the world at a fast pace.
This shipping company will deliver products no matter how small or big the scale of the order is.

This relational database management systems should have the following attributes:

Employees table:
Provides personal details about each employee.
With attributes such as Employee ID, first name, last name, title, reports to, date of birth, hire date, address,
city, region, postal code, country, phone number, email and salary.

Region table:
Identify the 5 main shipping orders. 
Region ID and the region description.

Territories table:
Shows the ID number and last name of the person who is handles that main shipping order.
Territory ID, the name of company and region ID.

Orders table:
Provides information on the order. From when it was order till the required date.
Order ID, order date, required date, shipped date, ship Via, freight, ship name, ship address,
ship city, ship postal code, ship region, ship country.

Order details table:
Provides more detailed information about what was ordered.
Order ID, unit price, quantity, discount.

Product table:
Should have specific entities about the product.
Product ID, product name, quantity per unit, unit price, units in stock, units in order, reorder level, discount, discontinued.

Categories table:
Informs you about the different types categories.
Order ID, unit price, quantity, discount.

Suppliers table:
Gives information about the companies that provides the products to Ship Station.
Supplier ID, company name, contact title, address, city, region, postal code, country, phone number, email.

Customers table:
Informs you of the companies that orders products from Ship Station.
Customer ID, company name, contact name, contact title, address, city, region, postal code, country, phone number, email.

Customer demographics:
Table describes the type of product that was purchase by which customer.
Customer Description and customer ID.

## Screenshots of Database:
### Diagram
<img align="center" width="750" height="500" src="https://user-images.githubusercontent.com/88590240/166157337-379a435f-a08f-4582-9882-00ee00d9622a.png">

### Insert
<img align="center" width="640" height="500" src="https://user-images.githubusercontent.com/88590240/166157707-d252952a-753a-4bd4-a4b3-0ae4378cf809.png">

### Joins
<img align="center" width="640" height="500" src="https://user-images.githubusercontent.com/88590240/166157428-5e1d1f53-4ef3-4d28-bcab-d34ec5664afb.png">

### Employees Table
<img align="center" width="640" height="500" src="https://user-images.githubusercontent.com/88590240/166157501-4624c6f2-176d-4abf-8b02-1f416e790a9d.png">
