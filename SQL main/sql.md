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
## **4) Update Database (UPDATE)** :
```
UPDATE products
SET price = 0.8
WHERE id = 2
```
## **5) Alter (Addtion or any other changes)** :
```
ALTER products
ADD stock INT
```
## **6) Delete** :
```
DELETE FROM products
WHERE id = 2
```
