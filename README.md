# Pizza-Delivery-website
Author Sailee Phal
<!DOCTYPE html>
<html>
<body>

<p><h1><center><b>Project Overview: Pizza Delivery Management System</b><center></h1>
This pizza delivery project involves the development of a database system to manage various aspects of a pizza delivery service. <br>
The system is designed to handle orders, track customer information and manage inventory.<br>
</p>
<p>
<h2>Key Components:</h2>

    <b>1.Orders Management:</b>
    <ul>
        <li>
        The orders table stores essential order details, including order ID, creation 
        timestamp, item information, quantity, customer ID, delivery status, and 
        delivery address.<br>
        </li>
        <li>
        Customers are identified and tracked using the customers table, which 
        contains customer IDs, first names, and last names.<br>
        </li>
    </ul>
    <b>2.Delivery Address:</b>
    <ul>
    <li>     
	    Delivery addresses are maintained in the address table, which includes 
        details like delivery address lines, city, and zip code.<br>
        Each address is associated with an add_id.
    </li>
    </ul>

    <b>3.Menu Items:</b>
     <ul>
        <li>The item table holds information about menu items, such as item IDs,names,  
          costs, sizes, and prices.
        </li>
     </ul>
</p>
<p>
<h2>Description of  Modules</h2>
<p>
<b>Customer Registration Module:</b><br>

Allows new customers to register by providing their contact information and delivery address.<br>
Provides the functionality to update or delete customer information.<br>
</p>
<p>
<b>Order Processing Module:</b><br>

Allows customers to place orders by selecting menu items and specifying quantities.<br>
Manages order details, including delivery status and addresses.<br>
Supports order updates and cancellations.<br>
</p>
<p>
    <b>Menu Management Module:</b><br>

    Enables the addition, modification, and removal of items from the menu.<br>
    Associates ingredients and prices with menu items.<br>
</p>
<p>
    <b>Inventory Management Module:</b><br>

    Tracks ingredient levels and ensures sufficient stock for menu items.<br>
    Alerts when ingredients need replenishment or when an item cannot be prepared due to low inventory.<br>
</p>
</p>
</body>
</html>
