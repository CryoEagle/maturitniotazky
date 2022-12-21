Zpět na [[Programování a databázové systémy]]

-   DDL – Data Definition Language.
-   DQL – Data Query Language.
-   DML – Data Manipulation Language.
-   DCL – Data Control Language.
-   TCL – Transaction Control Language.

## DDL

DDL jazyk kterým definujeme schéma databáze
-   [**CREATE**](https://www.geeksforgeeks.org/sql-create/): This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
-   [**DROP**](https://www.geeksforgeeks.org/sql-drop-truncate/): This command is used to delete objects from the database.
-   [**ALTER**](https://www.geeksforgeeks.org/sql-alter-add-drop-modify/)**:** This is used to alter the structure of the database.
-   [**TRUNCATE**](https://www.geeksforgeeks.org/sql-drop-truncate/)**:** This is used to remove all records from a table, including all spaces allocated for the records are removed.
-   [**COMMENT**](https://www.geeksforgeeks.org/sql-comments/): This is used to add comments to the data dictionary.
-   [**RENAME**](https://www.geeksforgeeks.org/sql-alter-rename/)**:** This is used to rename an object existing in the database.


## DCL

Práva uživatelů - přiřazení a odebrání práv
-   [**GRANT:**](https://www.geeksforgeeks.org/mysql-grant-revoke-privileges/) This command gives users access privileges to the database.
-   [**REVOKE:**](https://www.geeksforgeeks.org/difference-between-grant-and-revoke/) This command withdraws the user’s access privileges given by using the GRANT command.

## DQL

Pro vybrání dat z databáze
-   [**SELECT**](https://www.geeksforgeeks.org/sql-select-clause/)**:** It is used to retrieve data from the database.

## DML

upravuje data
-   [**INSERT**](https://www.geeksforgeeks.org/sql-insert-statement/) : It is used to insert data into a table.
-   [**UPDATE**](https://www.geeksforgeeks.org/sql-update-statement/)**:** It is used to update existing data within a table.
-   [**DELETE**](https://www.geeksforgeeks.org/sql-delete-statement/) : It is used to delete records from a database table.
-   [**LOCK:**](https://www.geeksforgeeks.org/sql-lock-table/) Table control concurrency.
-   **CALL:** Call a PL/SQL or JAVA subprogram.
-   **EXPLAIN PLAN:** It describes the access path to data.

## TCL

skupiny příkazů
Příkazy lze zpustit a následně pokud zjistíme že transakce neproběhla v pořádku je možné použít rollback.
-   [**COMMIT**](https://www.geeksforgeeks.org/sql-transactions/)**:** Commits a Transaction.
-   [**ROLLBACK**](https://www.geeksforgeeks.org/sql-transactions/)**:** Rollbacks a transaction in case of any error occurs.
-   [**SAVEPOINT**](https://www.geeksforgeeks.org/sql-transactions/)**:** Sets a save point within a transaction.
-   [**SET TRANSACTION:**](https://www.geeksforgeeks.org/sql-transactions/) Specifies characteristics for the transaction.
