# Gift Card
<img src ="https://github.com/nishadjadhav/GiftCard/blob/master/gift4.jpeg"/><img src="https://github.com/nishadjadhav/GiftCard/blob/master/giftcard.jpg" height=200 width=200/>


<p align="justify"> Magento 2 Gift Card extension allows store owners to create gift cards for customers to purchase and give their acquaintances as a present on special occasions. However, the problem comes from default Magento 2 Community Edition when it does not support gift card as a product. This product type only exists in Enterprise edition along with necessary functions to launch gift cards to the market. Hence, Magento 2 Gift Card extension solves this limitation by allowing admin to easily create gift card as a new product type with a system of code pattern, code generator, and management. Customers can buy gift cards, then send to other people via email or post office along with custom messages added in the purchase process. Store owners are provided with essential tools to keep track gift card purchases and even gift code usage.</p>

## Installation
#### Step 1: Upload the extension

1) Unzip extension package and upload them into Magento root directory
2) Enter the following at the command line

```sh
$ php bin/magento cache:flush
$ php bin/magento cache:clean
$ php bin/magento setup:upgrade
$ php bin/magento setup:di:compile
$ php bin/magento setup:static-content:deploy

```

## Features!
#### Flexible Configurations for Admin to Create and Manage Gift Cards
- #### Create a separate product Types for Gift cards
  Admin can add gift card product using seperate types of Gift Card Products types. Configure the price for various gift cards
Create, update or delete gift cards
  </br>	

  <img src="https://github.com/nishadjadhav/GiftCard/blob/master/Screenshot3.png" height="350" width="700">
  
- #### Manage gift card rules
  Manage gift card information (rules) in admin can check changing the status, balance and expiry date.
  </br>
  <img src="https://github.com/nishadjadhav/GiftCard/blob/master/Screenshot13.png" height="350" width="700">
  <img src="https://github.com/nishadjadhav/GiftCard/blob/master/Screenshot14.png" height="350" width="700">

- #### Configure and buy custom gift cards as wanted
  In the frontend gift card product in an product list, customers can select gift card product and place the order of these products
  </br>
  <img src="https://github.com/nishadjadhav/GiftCard/blob/master/Screenshot5.png" height="350" width="700">

- #### Send notification emails to Customer
  Once a buyer successfully orders a gift card, an automatic email along with gift card outcome will be sent to the customer   to confirm the order. The email sent to customer includes information of a message, a gift code and expiry day. Magento 2     Gift Card extension also notifies recipients when a gift code has been expired.
  <br>
  <img src="https://github.com/nishadjadhav/GiftCard/blob/master/Screenshot9.png" height="350" width="700">
- #### Apply gift card coupon code 
  Click on ->Apply Discount / Gift Code and enter Gift Coupon Code
  ( which is send on mail while purchasing Gift Card Product ) then click on
  ->Apply Discount.
  </br>
  <img src="https://github.com/nishadjadhav/GiftCard/blob/master/Screenshot11.png" height="350" width="700">
  </br>
  Coupon code gets applied successfully and Gift Card amount get deducted
  from total amount.

