# Confibeans - (Internship project under [Cere Labs](https://cerelabs.com/))

## About

Confibean is a Flask application responsible for developing micro-frontend dynamically whenever a JSON file is passed as an input to it. It allows companies to be able to create quick and clean UI for observing various forms of data on different suitable HTML components viz. folders, dropdowns, labels, containers, checkboxes etc. The entire process has been automated using recursion in pure javascript.
This project was developed during an internship for a company.

## Technology Stack

1. Backend developed using Flask
2. All logic applied through Javascript
3. JSON used for input data
5. Data Structures and Recursion application

## Flowchart

- User has to pass a JSON to the server.
- On the server lies the logic, which parses the entire JSON to form a tree data structure using recursion. 
- Once the tree is formed, another function is called that traverses through the tree in the down-up direction and starts rendering the UI.
- Recursively by moving upwards from leaf nodes the entire UI gets rendered.
- On changing any values of the data on the UI, the JSON is updated respectively.

## Features

- Get a more clean and neat way of viewing JSON files.
- It has a folder like structure similar to google drive and hence easy to use.
- Dynamically renders UI for the company, so running on JSON files becomes a lot more convenient.
