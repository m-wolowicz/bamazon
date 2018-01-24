# bamazon
Amazon-like storefront using MySQL and Node.js.

Trilogy Education Services Full-Stack Web Developer Program

University of Miami Cohort - 201710FSF3

Week 12 Homework Assignment: Node.js & MySQL

Create an Amazon-like storefront using MySQL and Node.js.

## Overview

Amazon-like storefront using MySQL and Node.js. The app takes in orders from customers and depletes stock from the store's inventory.  This application uses the MySQL and Inquirer npm packages.

## Instructions

### Customer View

1. From your Terminal, run the Node application called `bamazonCustomer.js`. Running this application will first display all of the items available for sale. Including the products' ids, names, and prices.

2. The app prompts the users with two messages:

    * The first asks them the ID of the product they would like to buy.
    * The second message asks how many units of the product they would like to buy.

3. Once the customer has placed the order, the app checks if the store has enough of the product to meet the customer's request.

    * If not, the app cancells the order due to  `Insufficient quantity!`, and then prevents the order from going through.

4. However, if the store _does_ have enough of the product, the app fulfills the customer's order.
    * It updates the SQL database to reflect the remaining quantity.
    * Once the update goes through, it shows the customer the information, including the total cost of their purchase.
    
5. Finally the app prompts the user again to see if they wish to continue shopping or if they are done.


## Screenshots & Video of Working App

1. Here is what the working app looks like:

    ![Customer View Screen Shot](/assets/images/CustomerViewScreenShot01.jpg)
    
2. Here is a quick video of the working app:

    ![Customer View Video](/assets/images/CustomerViewVideo01.gif)