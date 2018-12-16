# Bamazon

Bamazon is a command line app that allows users to enter as either a customer, manager, or supervisor.  Each role has different interactions with the MySQL database that holds the information.  Richmond Ampomah is responsible for all aspects of this application.

Technologies Used: Node, MySQL, Javascript

Description:

Customers have the ability to select the movie they would like to purchase by entering the ID and selecting the amount of tickets they would like to buy.  The chart updates the new quantity and product sales.

Managers have the ability to view products that are currently for sale, view low inventory, add to inventory, and add new product.  The currently for sale is a get request from the MySQL database.  The low inventory is a get request with a filter of stock quantity.  The add to inventory is a put request that updates stock quantity.  The add new product is a post request that adds a new movie to the selection.

Supervisors can choose between two actions.  View Product Sales by Department and Create New Department.  The View Product Sales by Department is a join table that records the total profit information.  The Create New Department is a post request that adds a department option for future movies.
