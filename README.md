# sql
SQL Portfolio
--Create a hockey store database

create table Hockey_Store (id integer primary key, item text, size text,quantity integer, price integer);

insert into Hockey_Store values (1, "jersey", "small", 10, 85);
insert into Hockey_Store values (2, "jersey", "medium", 12, 95);
insert into Hockey_Store values (3, "jersey", "large", 15, 125);
insert into Hockey_Store values (4, "jersey", "extra large", 20, 125);
insert into Hockey_Store values (5, "jersey", "2 x large", 117, 135);
insert into Hockey_Store values (6, "puck", "4 pack", 52, 13);
insert into Hockey_Store values (7, "gloves", "9 inch", 10, 30);
insert into Hockey_Store values (8, "gloves", "12 inch", 13, 40);
insert into Hockey_Store values (9, "gloves", "13 inch", 14, 50);
insert into Hockey_Store values (10, "gloves","15 inch", 16, 60);
insert into Hockey_Store values (11, "helmet", "black", 5, 75);
insert into Hockey_Store values (12, "helmet", "red", 3, 60);
insert into Hockey_Store values (13, "helmet", "royal", 5, 60);
insert into Hockey_Store values (14, "helmet", "white", 5, 75);
insert into Hockey_Store values (15, "helmet", "green", 5, 60);

--display the database ordered by price
SELECT * FROM Hockey_Store order by price;

--what is the avg price of jersey? 
SELECT AVG(price) "avg jersey item price"
FROM Hockey_Store
where item='jersey'; 

