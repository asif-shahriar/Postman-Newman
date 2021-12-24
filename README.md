# Postman-Newman
## Prerequisites:
* Install Postman 9.4.1
* Install Visual Studio Code 1.6
* Install Nodejs 16.13.1
## How to run this file:
* Download the **"Collection"** zip file
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

![Screenshot_1](https://user-images.githubusercontent.com/71173675/147214191-6e0357f9-dce2-46d3-af04-f4b91adc0fa1.png)
