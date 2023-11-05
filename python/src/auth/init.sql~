CREATE USER 'auth_User'@'localhost' IDENTIFIED BY 'Aauth123';

CREATE DATABASE auth;

GRANT ALL PRIVILENGES ON auth.* TO 'auth_user'@'localhost';

USE auth;

CREATE TABLE user(
  id INT NOT NULL AUTO:INCREMENT PRIMARY KEY,
  email VARCHAR(255) NOT NULL UNIQUE,
password VARCHAR(255) NOT NULL);

INSERT INTO user (email,password) VALUES ('georgio@email.com','Admin123')
