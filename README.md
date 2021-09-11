# Deliveroo API

Deliveroo API is the API to make my [Deliveroo web app](https://thirsty-lamarr-1b3108.netlify.app/) work. This API simply allows users to get all the menus of the restaurant *Le Pain Quotidien*.

Note that data is stored as a simple `json` file which is returned to the frontend.

Frontend project is here: 👉 [Frontend](https://github.com/Remi-deronzier/deliveroo-frontend)

## Prerequisties

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of `node.js`
* You have a `Windowd/Linux/Mac` machine.

*Option : you can install [Postman](https://www.postman.com/) to easily make requests.*

## Installing Deliveroo API

Clone this repository:
```
git clone https://github.com/Remi-deronzier/deliveroo-api.git
cd airbnb-api
```

Install packages:
```
npm i
```

Create a `.env` file at the root of the project and store the following environment variables:
```
PORT = <the-listening-port-of-your-server>
```

When installation is complete, run the project:
```
npx nodemon index.js
```

## Route documentation (main routes)

### / (GET)
Get all the menus of the restaurant


