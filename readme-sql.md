# readme-sql

# To set up users table: 

CREATE TABLE users (username varchar(255) PRIMARY KEY, 
    password varchar(255));

INSERT INTO users (username, password) VALUES ("Amelia-Earhart",  "Youaom139&yu7");
INSERT INTO users (username, password) VALUES ("Otto",  "StarsWars2*");


# To set up ratings table: 

CREATE TABLE ratings (id INTEGER(1) PRIMARY KEY AUTO_INCREMENT,
    username varchar(255),
    song varchar(255),
    rating INTEGER(1));

INSERT INTO ratings(username, song, rating) VALUES ("Amelia-Earhart",  "Freeway", 3); 
INSERT INTO ratings(username, song, rating) VALUES ("Amelia-Earhart",  "Days of Wine and Roses", 4); 
INSERT INTO ratings(username, song, rating) VALUES ("Otto",  "Days of Wine and Roses", 5); 
INSERT INTO ratings(username, song, rating) VALUES ("Amelia-Earhart",  "These Walls", 4); 

# To set up artists table: 

CREATE TABLE users (song varchar(255) PRIMARY KEY, 
    artist varchar(255));

INSERT INTO artists(song, artist) VALUES ("Freeway", "Aimee Mann"); 
INSERT INTO artists(song, artist) VALUES ("Days of Wine and Roses",  "Bill Evans"); 
INSERT INTO artists(song, artist) VALUES ("These Walls", "Kendrick Lamar"); 

# CASCADE?