# Installation

This project is fork from https://github.com/AndrejPHP/w3schools-database.git

This project contains w3School.sql having the follwing tables

    categories
    customers
    employees
    orders
    order_details
    products
    shippers
    suppliers
    
### Graphical View of Schemas with their relations
![Alt text](https://raw.githubusercontent.com/majorsabbir/sql_practice/master/w3schools.svg)

To up and running fork this project first from https://github.com/majorsabbir/sql_practice.git if not did already
```
git clone https://github.com/majorsabbir/sql_practice.git
cd sql_practice
docker-compose build
docker-compose up -d
```

Now open http://localhost and use ```mariadb``` as host, ```root``` as user and ```root``` as password

Import this ```w3School.sql``` file.
