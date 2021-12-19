## Getting Started

Welcome to Faculty Registration System.

## Folder Structure

The workspace contains two folders :

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

## Dependency Management

- MySQL Connector
- MySQL Database
- Java v10.0.2

## Initialization

- Restore db from the db dump file "mysqldump.sql" using command 
```
mysql -u <username> -p facultyRegister < mysqldump.sql
```
- Update your MySQL conf in UserRegistation.java MySQL conf section
- Set MySQL connector in Referenced Libraries
- Run the project.