# Dairy-Firm-Management-System
Control and manage a dairy firm in an efficient way

Table for stuffs


CREATE TABLE Stuff(
     ID VARCHAR(100) PRIMARY KEY,
     username VARCHAR(20) NOT NULL, 
     address varchar(50) NOT NULL
);


Table for admin

CREATE TABLE admin(
     ID VARCHAR(100) PRIMARY KEY,
     username VARCHAR(20) NOT NULL, 
         password varchar(50) NOT NULL

);

Table for seller

CREATE TABLE seller(
     ID VARCHAR(100) PRIMARY KEY,
     username VARCHAR(20) NOT NULL, 
      phone_number int(20) NOT NULL, 
     address varchar(50) NOT NULL
);