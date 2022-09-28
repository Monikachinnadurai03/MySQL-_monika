# Code to create a table
create table student(
    roll_no int primary key,
    name varchar(30) not null,
    dept varchar(30) not null,
    age int not null
);

# Code to insert a  table
insert into student values(1,'Jerome','ECE',18),
			   (2,'Ishu','BIO',17),
                           (3,'Ajitha','MECH',20),
                           (4,'Vivega','IT',19),
                           (5,'Anu','ECE',21),
                           (6,'Raja','CSE',17);

# Code to describe a table                           
describe student;

# Code to read a table
select * from student;
select name,dept from student;

# Code to delete a table
drop table student;

# Code to update a table
update student set name = "Kavi" where roll_no = 6;

# Code to alter a table
alter table student
 rename column roll_no to reg_no;
