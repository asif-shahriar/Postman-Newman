# Postman-Newman
## Prerequisites:
* Install Postman 9.4.1
* Install Nodejs 16.13.1
## How to run this file:
* Clone the repo
* Open terminal in root folder
* Give following commands:
```
npm i newman
```
```
npx newman run .\collection\customers_collection.json -e .\collection\customerEnv.json -n 1
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js 
```

This is the snapshot of the **index.html** file

![Screenshot_1](https://user-images.githubusercontent.com/71173675/152147529-4fe5ae30-f12b-42b5-a24c-131f3322d3c0.png)

