relation table

cid	pid
101	202
566	322
875	345

people table



create table relation(
cid int,
pid int
)

insert into relation(cid,pid)values(101,202)
insert into relation(cid,pid)values(566,322)
insert into relation(cid,pid)values(875,345)
select * from relation;


create table relation(
id int,
name varchar(255),
gender varchar(255)
)

id	name	gender
101	Riya	F
566	Aman	M
202	Rakesh	M
875	lucky	M
202	Reena	F
322	Raina	F
345	Rohit	M
322	Mohit	M
345	Meena	F

insert into people(id,name,gender)values(101,'riya','F');
insert into people(id,name,gender)values(566,'Aman','M');
insert into people(id,name,gender)values(202,'Rakesh','M');
insert into people(id,name,gender)values(875,'lucky','M');
insert into people(id,name,gender)values(202,'Reena','F');
insert into people(id,name,gender)values(322,'Raina','F');
insert into people(id,name,gender)values(345,'Rohit','M');
insert into people(id,name,gender)values(322,'Mohit','M');
insert into people(id,name,gender)values(345,'Meena','F');
