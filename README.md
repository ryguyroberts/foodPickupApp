# Food Pickup App

Food Pickup is a single-page app that allows users to place orders with a restaurent. While allowing both the client and the restaurant to recieve SMS texts for orders.

## Final Product

### Main Menu
!["Main Menu"](https://github.com/ryguyroberts/foodPickupMidterm/blob/master/docs/main%20page.png?raw=true)
### Cart
!["Cart"](https://github.com/ryguyroberts/foodPickupMidterm/blob/master/docs/cart%20page.png?raw=true)
### Orders
!["Orders"](https://github.com/ryguyroberts/foodPickupMidterm/blob/master/docs/order%20page.png?raw=true)


## Dependencies
- Chalk
- Express
- Cookie-session 
- Node (V14+ for Twilio)
- Dotenv
- Ejs
- Pg
- Twilio

## Dev Dependencies

- Nodemon

## Getting Started

- Install all dependencies (using the `npm install` command).
- Run the development web server using the `node server.js` command OR NPM start.
- Set up PSQL DB info and Twilio API credentials in .env(As well as twilio # to text from and number to text in /public/javascript/network.js)
- Access at http://localhost:8080/ can modify port in node server/index.js config if needed.
