# Final-Hackathon---Travel-Card-Navigator

## Problem Statement

This international travel card from a leading commercial bank is popular with both the bank's own customers and customers of other banks. The bank's business team is eager to provide consumers with a variety of card usage analysis in the form of a dashboard that shows spending and allows users to easily search for transactions.

Could you please design a personalized dashboard that consumers can access from any of their devices or computers?

## Pro-Tip :
Go to https://github1s.com/AaarchiGandhi/Travel-Card-Navigator-A-Full-Stack-Application for browsing through the code in the browser itself.

Go to https://drive.google.com/drive/folders/1euOfPIe8I2qMrawu5dVd895MFpVpHRO6?usp=sharing for seeing the glimpse(some snapshots of each module) of our Full Stack Application for both Laptop view and Responsive device (preferably designed for Pixel 2)

## Work Done
- Developed a full-stack web application " Travel-Card-Navigator " from the ground up, providing real-time international travel card usage analysis to users in a customized dashboard.
- Utilized the Chart.js library to visualize user data in interactive charts on the dashboard, and incorporated a card blocking feature for registered users.
- Enabled users to analyze their spending by category, month, and other criteria, and quickly search their transaction history.
- This application has    
                1). Implemented a user registration page for non-registered users. <br>
                2). Developed a user login page for registered users. <br>
                3). Created a personalized dashboard to display real-time transaction data in the form of charts. <br>
                4). Integrated a search functionality module to enable users to search and filter their past transactions. <br>
                5). Added a card blocking feature to protect users in case their card is stolen or lost. <br>
                6). Developed a payment module to facilitate various types of transactions. <br>
                7). Incorporated a header, hero unit, and footer in the application homepage using the Angular ng-carousel component. <br>
                8). Implemented a PageNotFoundException module to handle cases where the link is broken or invalid. <br>
                9). Utilized the Currency layer API to convert from one currency to another since consumer spendings are always displayed in the home currency. <br>
                10). Optimized the application for responsive design on the Pixel 2 device. 

- The personalized dashboard of a user displays charts and graphs that illustrate their real-time transaction data are:<br>
                1). Monthly spending breakdown. <br>
                2). Category-wise transaction volume. <br>
                3). City-wise transaction volume



## Technologies Used :

### FrontEnd
HTML, CSS, Carousel, Angular, Angular Material, JS Charts, Currency Layer API

### BackEnd
Spring Boot

### DataBase
MongoDb (since the data was unstructured)


Note:  "payment-done" is the main and final branch

## Steps to run the applications :-

Prerequisites:

-> Install Node.js
-> Install MongoDB

To run the full-stack application:

1) Open the front-end folder in Visual Studio Code and run the following commands:
    
    npm install
    ng serve -o

2) Start MongoDB on your local system.

3) Open the back-end folder in IntelliJ IDEA and run the following Java applications in the following order:

    ServicediscoveryApplication.java
    GatewayApplication.java
    ContactApplication.java
    PaymentApplication.java
    UserAuthenticationApplication.java

4) Open the full-stack application in your local web browser at http://localhost:4200.
