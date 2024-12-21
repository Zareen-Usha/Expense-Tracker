create table userTable (userid varchar(30) primary key, name varchar(30));

create table expenditure(id int, 
expenseName varchar(30), 
amount float, 
userid varchar(30),
foreign key(userid) references userTable(userid));