# KPNAssignment
This project is developed part of the Lightning web component Assignment. We are building a order Product operations and custom related list experience using LWC in Salesforce. This project is just for demonstration. 

#Developer
Anita Satpute

## 🚀 Quick Start
The above assignment mainly have 3 LWC components:

## 1. OrderProductOperations**
-In this LWC component we are displaying the products based on the Price book attached to order.
-In this LWC component we are also performing some basic validations.
-We have added 'Add Product' Button in LWC which is calling controller call to add order item and once its successfully added we are sending massage to other LWC component to refresh the data.
-We are also calling pagination component from this component 

## 2. OrderProductRelatedList
-In this LWC component we are fetching the backed data ot order item and displaying it on UI.
-We are also listning the message in this LWC component from OrderProductOperations to reload the cirrent table content.

## 3. OrderConfirmation 
-In This LWC component we have created a button to confirm the order, which is calling backend and sending a request to https://requestcatcher.com/ and geting response.
-In the serversidecontroller of this LWC component we are also activating the order.
-On UI once the backend actions are successfully completed we are refreshing the record to show the backend changes.




