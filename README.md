# tipsy-tourist-server

## Installation

 - Clone this repo

 - In terminal (Mac), run:

```
cd tipsy_tourist_server
npm install
```
You will need to request a Google API key [here](https://cloud.google.com/) and then create a new file apiKey.js in the src directory with the following code:

```
const apiKey = "<YOUR-API-KEY>"
module.exports = apiKey
```

## Running locally

```
cd tipsy_tourist_server
npm start
```

In order to run Tipsy Tourist in the browser you will also need to run the front end - [click here](https://github.com/HOOLAHAN/tipsy-tourist) to be directed to this repo
