# Postman-Newman
## Prerequisites:
* Install Postman 9.4.1
* Install Visual Studio Code 16.11.8
* Install Nodejs 16.13.1
## How to run this file:
* Import collections to VS code
* Open terminal
* Give following commands:
```
npm i newman
```
```
npx newman run .\collection\customers_collection.json -e .\collection\customerEnv -n 1
```
```
npm i newman-reporter-htmlextra
```

