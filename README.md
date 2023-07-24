# Notes-SQL
activity QL6 and QLC
SQL Commands 

select * from teams as t
where t.id > 1 and t.id < 4;

select * from 


QLC
As a developer I want to design and add a dogs table to the dogs' application 
so that when i run the application the table is populated with data
1.   create the SQL shcema



   create table owners(id int AUTO_INCREMENT PRIMARY KEY, name int not null);

      create table dogs (id int NOT NULL, name varchar(50) NOT NULL, age int, owner_id int, FOREIGN KEY(owner_id) references (id));

      insert into owners(name)
      values (1);

      select * from owner;

      insert into dogs (id, name, age, owner_id) values (1, 'Max', 12, 1), (2, 'Jack', 9, 1);

      
3.   test the shcema
4.   
