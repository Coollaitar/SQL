## **1) For Inserting Info use (UPDATE)** :

```
INSERT INFO database_name (column names)
VALUES (values of each column)
```

## **2) Create Database (CREATE)** :

```
CREATE TABLE products (
id INT NOT NULL,
name STRING,
price MONEY,
PRIMARY KEY (id)
)
```

## ** 3) Read Data from Database (READ)** :
```
SELECT * FROM products WHERE name="Pencil"
```
