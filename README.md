# Data-Platform-WIT
Notbooks
Notebook-Queries.ipynb file contains basic data science queries.

1. Azure Portal  - for this, user needs to have Azure subscription.If you have visual studio subscription then you will get around 120£ free credit.

One or more tools should be installed into your local machine.
1. SSMS - Sql server management studio.(Local Machine) 
    - Installation Links https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15
2. ADS  - Azure Data Studio.(Local Machine) 
    - Installation Links https://azure.microsoft.com/en-gb/services/developer-tools/data-studio/

Notebook-Queries.ipynb file has basic datascience - data cleansing/data preparation/data visualizaion queries.Following table should be created with data.

Table creation & Data Insertion

  CREATE TABLE movies(
    id INT IDENTITY(1,1) PRIMARY KEY,
    name VARCHAR(200) NOT NULL,
    rating int NULL
);

-------------------------
select * from [dbo].Movies
----------------------
insert into [dbo].[Movies](name,rating) values('FF9',NULL);
insert into [dbo].[Movies](name,rating) values('MI3',NULL);

insert into [dbo].[Movies](name,rating) values('FF6',0);
insert into [dbo].[Movies](name,rating) values('MI2',0);

insert into [dbo].[Movies](name,rating) VALUES('DIE ANOTHER DAY',5.0); 
insert into [dbo].[Movies](name,rating) VALUES('SKY FALL',4.0); 

insert into [dbo].[Movies](name,rating) VALUES('TAXI',0.0); 
insert into [dbo].[Movies](name,rating) VALUES('WHO KILLED HER',2.0); 

insert into [dbo].[Movies](name,rating) VALUES('MI5',5.0); 
insert into [dbo].[Movies](name,rating) VALUES('MI6',4.0); 

insert into [dbo].[Movies](name,rating) VALUES('DRIVE',5.0); 
insert into [dbo].[Movies](name,rating) VALUES('HERO',4.0); 

insert into [dbo].[Movies](name,rating) VALUES('BABY DRIVE',''); 

insert into [dbo].[Movies](name,rating) VALUES('DIE ANOTHER DAY 2',5.0); 
insert into [dbo].[Movies](name,rating) VALUES('SKY FALL 2',4.0); 

insert into [dbo].[Movies](name,rating) VALUES('FF8',5.0); 
insert into [dbo].[Movies](name,rating) VALUES('FF6',4.0); 

