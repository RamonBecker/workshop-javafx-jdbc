# Workshop JavaFX JDBC
 
## :information_source: Information 

The project was developed using JDBC and the DAO pattern. A simple CRUD of Sellers and their Departments was performed.

## ⚠️ Prerequisite
[![Java Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/br/java/technologies/javase-downloads.html) >= 11 

![Mysql Badge](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

## Demo

![tela1](https://user-images.githubusercontent.com/44611131/135714588-6d12f673-1006-4a76-8cae-0e943018271d.PNG)
![tela2](https://user-images.githubusercontent.com/44611131/135714590-8ae53cf0-7bf3-4793-9a21-f06987adec9c.PNG)
![tela3](https://user-images.githubusercontent.com/44611131/135714593-288f9f15-ef95-425d-ad85-c2d380c98d74.PNG)
![sellerform](https://user-images.githubusercontent.com/44611131/135714595-fd847ca7-5157-4c8a-9d73-42d8752679cc.PNG)

## :rocket: Installation

To install the project you must install mysql on your machine.

## ⚙️ Installing MySQL

Enter the following commands in the terminal.

```
sudo apt update
sudo apt install mysql-server

```
### Configuring MySQL

For new installations, you will want to run the security script that is included. This changes some of the less secure default options for things like root logins and example users. Enter the command below.

```
sudo mysql_secure_installation
```
This will take you through a series of prompts where you can make some changes to the security options of your MySQL installation. The first prompt will ask you if you want to configure the Validate Password Plugin, which can be used to test the strength of your MySQL password. Regardless of your choice, the next prompt will be to set the password for the MySQL root user. Sign in and then confirm a secure password of your choice.

From there, you can press Y and then ENTER to accept the default answers for all subsequent questions. This will remove some anonymous users and the test database, disable remote login for root, and load all of these new rules so that MySQL immediately respects the changes you made.

### Testing MySQL

To see if MYSQL is running, type the following command.

```
systemctl status mysql.service
```

If MySQL is not running, you can start it with the following command.
```
sudo systemctl start mysql

Now try to connect your root user to MySQL.
```
mysql -u root -p

### Create the database in MySQL

```
CREATE DATABASE coursejdbc
```


Before running the script to create the tables, check the properties file and change the user and password for your configuration. And then run the following script:

```
https://drive.google.com/file/d/1ZuXEOee1Yd11YPIG74tTjhGbkMLUL9sv/view?usp=sharing
```

![](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)


```
git clone https://github.com/RamonBecker/workshop-javafx-jdbc.git
```

![](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
```
git clone https://github.com/RamonBecker/workshop-javafx-jdbc.git
or install github https://desktop.github.com/ 
```

## :zap: Technologies	

- Java
- JDBC
- MYSQL
- DAO


## :memo: Developed features

- [x] the user can register a department;
- [x] the user can delete a department;
- [x] the user can edit a department;
- [x] the user can list the departments;

- [x] the user can register a seller;
- [x] the user can delete a seller;
- [x] the user can edit a seller;
- [x] the user can list the sellers.


## :technologist:	 Author

By Ramon Becker 👋🏽 Get in touch!



[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/RamonBecker)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/https://www.linkedin.com/in/ramon-becker-da-silva-96b81b141//)
![Gmail Badge](https://img.shields.io/badge/-ramonbecker68@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ramonbecker68@gmail.com)
