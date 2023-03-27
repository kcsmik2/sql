# sql
SQL Portfolio
create table Hockey_Store (id integer primary key, item text, size text,quantity integer, price integer);
insert into Hockey_Store values (1, "jersey", "small", 1, 100);
insert into Hockey_Store values (2, "jersey", "medium", 1, 100);
insert into Hockey_Store values (3, "jersey", "large", 1, 100);
insert into Hockey_Store values (4, "jersey", "extra large", 1, 100);
insert into Hockey_Store values (5, "jersey", "2 x large", 1, 100);
insert into Hockey_Store values (6, "puck", "black", 1, 100);
insert into Hockey_Store values (7, "gloves", "9 inch", 1, 100);
insert into Hockey_Store values (8, "gloves", "12 inch", 1, 100);
insert into Hockey_Store values (9, "gloves", "13 inch", 1, 100);
insert into Hockey_Store values (10, "gloves","15 inch", 1, 100);
insert into Hockey_Store values (11, "helmet", "black", 1, 100);
insert into Hockey_Store values (12, "helmet", "red", 1, 100);
insert into Hockey_Store values (13, "helmet", "royal", 1, 100);
insert into Hockey_Store values (14, "helmet", "white", 1, 100);
insert into Hockey_Store values (15, "helmet", "green", 1, 100);
SELECT * FROM Hockey_Store order by size;
SELECT * FROM Hockey_Store;
