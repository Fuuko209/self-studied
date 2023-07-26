torization## Table of Contents
- [SQL](#sql)
- [Python](#python)
- [Power BI](#power-bi)
- [Power Platform](#power-platform)
- [Analytical Thinking](#analytical-thinking)
- [Digital Marketing and E Commerce](#digital-marketing-and-e-commerce)
- [Google UX Design](#google-ux-design)
  
# SQL
| Knowledge Link | Completion Date | Knowledge Description | 
|---|---|---|
| [Data Fundamentals](#data-fundamentals) | 27/05/2023 | An overview of data, what is data, where it comes from, an introduction to databases, database management systems (DBMS), and the SQL data query language|
| [SQL Fundamentals](#sql-fundamentals) | 27/05/2023 | An overview of SQL, type of SQL commands |


### Data Fundamentals

**Type of Data**
| Qualitative Data| Quantitative Data |
|---|---|
| Determine the "**characteristics**" of an object or subject | Determine the "**quantity**" or numerical measurements of an object or subject. |
|![image](https://github.com/Fuuko209/self-studied/assets/103474817/f7d07f6f-f472-4c2b-80b8-cf8805ac0cb1) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/83d4b653-bfcb-4146-a3e2-c20aa0f8b78a) |

**Database**

A database is a structured collection of data that is organized and stored in a way that allows for efficient storage, retrieval, and manipulation of the data.
| Relation Database | Non Relational Database |
|---|---|
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/d0ea5af1-7ed1-4a05-9714-19af7cf6ae5b) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/1ca9d3a1-e10b-4e7b-b6cd-3c7079f279a5) |

**Database Management System (DBMS)**
is software designed to define, perform operations on, retrieve, and manage data within a database.

**Relational Database Management System (RDBMS)**
is a type of database management system that is based on the relational model of data, such as MySQL, Oracle, SQL Server...

**Structured Query Language (SQL)**
is a standard programming language used for managing and manipulating relational databases.

### SQL Fundamentals


**SQL Types**



![image](https://github.com/Fuuko209/self-studied/assets/103474817/a8b99d1e-fcb4-4b37-9a3d-7002e61ac1cc)



| Data Type | Description |
|---|---|
| Character |  - **CHAR** : store fixed-length character strings with a predetermined length. - **VCHAR**: store variable-length character strings. - **TEXT**: store character strings with a length larger than CHAR and VARCHAR (> 255). - **NCHAR**:  is similar to CHAR but is used to store Unicode character strings. - **NVARCHAR**: is similar to VARCHAR but is used to store Unicode character strings. - **NTEXT**: is similar to TEXT but is used to store long Unicode character strings. |
| Numeric | -**Exact Numeric**: numeric/int-tinyint-smallint-bigint/decimal/money-smallmoney/bit. -**Appropriate Numeric**: float/real |

**Type of SQL Commands**

![image](https://github.com/Fuuko209/self-studied/assets/103474817/c3172f50-26da-4306-9799-da55d5a2bb54)

**DDL commands (Database Define Language)**
| Command | Syntax | Example
|---|---|---|
| CREATE |![image](https://github.com/Fuuko209/self-studied/assets/103474817/96dd7117-a3c5-4eb9-8acf-1b2b58e02538) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/d0aa0b3e-3882-4586-8524-28f371653a24) |
| ALTER | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/36230784-9994-4c2c-bc7c-f18eae00e5d3) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/5433915c-94ae-42ba-90db-6f62afe81c50) |
| DROP | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f0d3894e-aa97-41c5-94f7-cbe68033c1ad) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/9ab0fe9b-107a-425b-ae29-100f7ac923b8) |
| TRUNCATE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/926ff3c9-44b2-4e10-8ccf-be74f18baac4)  ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b9f50d66-4510-4839-b7be-ba5a723f4232) |

**DML commands (Database Manipulate Language)**

| Command | Syntax | Example |
|---|---|---|
| INSERT | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/63c624ab-91ac-4c87-915c-fcec47a33dd3) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b749f1bf-2752-4f2f-85c9-70577a20155e) |
| UPDATE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/55c23c6d-bf9c-4745-ba19-f168978282eb) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/ea2072e4-d305-4a63-b37a-4921de8aa1b2) |
| DELETE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/02793ed7-86f9-4de8-a967-d5029c53a25a) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/9b9df31d-4b33-4ee7-b5d8-c520a2aa0c93) |
|WHERE | | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/8ad31093-8d5c-4cf9-89b3-b03ae385737a) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/5f8e15d8-c3be-41a1-917b-e4c03a8c1c01) |
**SQL statement execution order**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3a57fb38-3529-48f8-9add-bc593b742528)


**DQL commands (Database Query Language)**

| Command | Syntax | Example |
|---|---|---|
| TOP | | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f7e796c3-892c-4b5e-b909-bc413336d717) |
| DISTINCT | | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/216b43e4-cf9d-400a-9c42-cb8a151bbcea) |
| ORDER BY | | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/03c0ebb6-8bdb-4224-92de-0fc85a9658ef) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/9d0b4475-b609-4ffa-a342-c5c146071a87) |
| AND | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/2f03cb1b-3dcd-4453-b88a-b824804d5743) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/684acc73-6145-40ee-bd75-a41a7e53dcce) |
| OR | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/79df8105-a662-403f-adef-0024aee23375) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f2876eaf-f793-442b-be2a-ce8d34d9c4e1) |
| IN | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/a1118635-1f24-48c7-baf1-399f1ba2a65c) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/ee5cab19-efcb-48bb-8b3e-b1aa55fbde4f) |
| NOT | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b3b6b082-875b-4f94-bd61-b74699d99be7) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/5241f91b-ffcb-4b6c-8138-a2ac18822c3a) |
| BETWEEN | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/53a82120-1d78-4687-9e09-48fe00d8dc21) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/1992ab67-28c2-4fce-a3cd-e5d9489db39a) |
| LIKE | - The **"%"** symbol is used as a wildcard to represent zero, one, or multiple characters in a search pattern. - The **"_"** (underscore) character is used to represent a single character in a search pattern. ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b0ce84d6-baad-4df6-982e-c77cd15f2956)  |  ![image](https://github.com/Fuuko209/self-studied/assets/103474817/558738ab-76f0-4b2d-abab-9165f860f460) |
| "+", "-", "*", "/", "%", ROUND, FLOOR, CEILING|
| IS NULL / IS NOT NULL | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/4c9f401e-11b5-4bdd-9bb2-7794371c9090) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/a1288369-2412-4700-a970-1b9f12e1bb44) |
| ISNULL | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/16c1e09a-bc1b-402c-a79c-aaa3b6a57425) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b96d8ef2-17d6-4ede-8c4e-9c8c3eb505bf) |
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/0484ba39-6ee9-4333-9912-4f608046987d)| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/e84ff36f-9dc4-4aec-99ba-cbde3e928914) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/0c356cb3-b395-455a-82cc-d9c490793558) |
| UNION / UNION ALL| Have to ensure : 1. The number of columns, 2. Data types. UNION: eliminates duplicate rows from the final result set.UNION ALL: does not remove duplicate rows.![image](https://github.com/Fuuko209/self-studied/assets/103474817/d078c05c-7e9e-4cdd-8a7b-bb988dac860a) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/dbdc5867-acff-4313-9d9c-d23dadb6a7b6) |
| DATEDIF | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/1e6dbbc0-7164-43f1-a506-81f80f8da6f3) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/27fd02e0-5691-4d4f-88ed-a3a5222d63a4) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/129aad09-0919-4da7-9a9e-b3d508df1a31) |
| DATEPART | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/e4a577e8-0549-4905-a986-1dee6d67fbc4) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/be2da12e-1ebd-4406-8ed1-df6ef4afee69)| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/73f72d86-8147-4839-9a44-b852a62b5f98) | 
 | CURRENT_TIMESTAMP | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/58a286da-e85a-453f-8c96-ebdfc6d0b184) |
 | DATEADD | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f67bb839-e97c-47fa-8848-c81b23df47d3) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/69af9d6b-8915-425d-8999-bf66d529785d)
| DATEFROMPARTS | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/110263f8-0bac-41e0-a20d-845ca5d8e84d) |
| DATENAME | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/37ab1c31-0dc0-4fad-a20b-a9b0ea76304a) ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b97bf578-1886-4f07-acdd-e1d4ba339848) |
| DAY | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/4426522f-2973-4092-bd1a-4db69b154409) |
| MONTH | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/d9f70e99-7efe-4b26-9d03-b709dfb80034) |
| YEAR | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/2c53e939-cc77-4a80-a0ff-245071d29775) |
| GETDATE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/46619a47-e6ae-43b7-8a43-0b0b13bdfa8f) | 
| GETUTCDATE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/00e66da6-99e0-4b77-9563-1fc5a30b89f6) |
| SYSDATETIME | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b204fe33-838c-4415-8c00-a1a355968ee2) |
| CAST | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/4e4f8e20-be7b-492a-a015-06fb0c171197) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/83b301cd-64d2-4498-9462-236e4a268330) |
| CONVERT | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/da34cc12-95e8-448c-906c-882a8bf1c79a) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/94c3998a-869a-4ca2-8dcf-0d1bcfa6b86a) |
| COALESCE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/c5c61c84-96d1-43ac-b710-fbc5988ab73e) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/36bdaf71-a8f0-4650-8aef-5dfacf348f8f) |
| ISNULL | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/70f29402-c964-4a69-a20b-10edc6dd3dd1) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/29f63006-11c1-4b5a-a747-fb87e0017cb4) |
| ISNUMERIC | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/a94c54ad-e803-4459-b4a9-762a3b4cecad) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/04934720-565c-4588-9c25-efa7e54e654f) |
| ISDATE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/8ed5075b-ff87-489e-b2ed-8645cddd1aa2) |
| CONCAT | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/ded46e7d-30ce-4ead-afa2-a027e55bdc6d) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/da0c571b-8066-49ac-adee-f5902dc221c2) |
| REPLACE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/859c4076-508e-4bea-93c6-6d7808836c8c) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/c772c7c8-dbed-4e53-bf6b-e805cf139850) |
| REPLICATE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/568ae8dc-0b7f-41af-b7d4-74c1b72bcd6c) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/dc3d371b-1e30-4a35-aaf9-810c2826ad4f) |
| REVERSE | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/0fefb869-ded0-4a4f-824a-e99499c5c099) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/4f99ec19-239a-4f25-878c-6c0ed588e6b7) |



**Primary Key & Foreign Key**
| Primary key | Foreign key |
|---|---|
| Primary key is a column used to uniquely identify rows in a table. It is required to have a unique value (UNIQUE) and cannot contain NULL values. A table can have only one primary key.|Foreign key is a column used to reference another table by linking it to the primary key of that table.|
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/235f920b-5130-4d01-a1b5-7c1bbb6dab4f) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/d343bc29-8c0d-4bae-bad8-2ff89c192871) |
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b635c154-0964-48ff-9e9d-1eb3d69c0acb) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/64f5fdbb-2579-41fa-a4a6-541321d45d2c) |
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f7beffcf-573a-4817-94c4-0ed793a181b4) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/480ec3b2-bea6-443f-b857-753900766b49) |

**The relationships** between tables in a relational database are commonly classified into three types: One-to-One (1:1), One-to-Many(1:N), Many-to-Many (N:M)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/65a4befb-764e-42cd-802d-ee7fdf1bfe5e)

**Case When**
| Simple Case | Searched Case |
|---|---|
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/59592e59-4ee2-464c-aee6-5eeaad83e303) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f10c0608-b886-4789-b89f-09570b6d7445) |

**Subquery**
Subqueries can be nested within clauses of a query statement like:
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7782f579-ee3e-4e16-aaa4-26d740dbbb8e)




**CTE**(Common Table Expression)
Have to use them within the main query; if trying to run the CTE separately, the query statement will throw an error.
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3f8b8929-d6b6-4333-b55b-044562ed9f85)



**Window Function**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6b58d90c-2b07-4972-8eb9-f8b1aee3b9e4)


Window_Function:
| Aggregate Functions | Ranking Functions | Analytic Functions |
|---|---|---|
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/7e7b3e02-afa5-4bbc-b236-52101411cb9e) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/2a309ec4-0c75-4b27-9db0-4ca537c3819f) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/45913f02-8640-4dc3-bead-4c3f740cf54e) |

![image](https://github.com/Fuuko209/self-studied/assets/103474817/ce06a51d-c690-4cad-abb9-781a92ea5d38)
Lower Bound needs to be placed BEFORE the Upper Bound




# Python

| Knowledge Link | Completion Date | Knowledge Description | 
|---|---|---|
|[Fundamentals](#fundamentals) | 25/07/2023 | |
|[Numpy](#numby) | 25/07/2023 | |
|[Pandas](#pandas) | 25/07/2023 | |
|[Dataframe](#dataframe) | 25/07/2023 | |



### Data Type
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f11f3211-b2ff-4b6a-8e1b-529e185199a9)
 USE TYPE FUNCTION TO DETECT DATA TYPE
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c626686f-2b9b-4030-9ac1-8007da1500b0)
USE TYPE CONVERSION
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d390a732-089b-4f72-bfd2-ef89fce2315f)
MUTABILITY
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d8e206c0-1bbf-4c54-9b3b-bbe7cb5dee9e)
VARIABLES NAMING RULES
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f4d2a7df-5fd4-436c-9c87-e7e2bc6e3e8a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/14e93f0a-a24a-415f-9129-d45ba1a79871)
TRACKING VARIABLES
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d94f129e-1b99-4a96-ad2a-d8856f48a467)
ARITHMETIC OPERATORS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e6b9a16a-b46c-4e8a-b2d6-375511fede00)
ORDER OF OPERATIONS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1255cb6a-f29c-4b90-8223-3b75c55cbce4)
STRING SLICING
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c77ed905-40da-473b-81f7-8599a94429a9)
STRING METHODS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/feacab51-5200-4c24-a177-4cdfb1e78eea)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/5e8c6e85-7756-49ab-b78b-e870ea0aa04d)
F-STRINGS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/851812f5-d32b-4c32-b6d1-c7cc21defd3e)
COMPARISON OPERATORS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/56512c48-c9a4-4574-9a35-3ce89dc22cb0)
THE IF STATEMENT
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fa67cb05-a8ee-41a9-8797-ac2dd1cd3cc5)

**LIST**
UNOACKING LIST
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a77af057-0334-4eda-bdda-8d5d17995d98)
CHANGING LIST ELEMENTS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f71cfba8-ea2b-46ae-92e8-d2e560804dd5)
ADDING LIST ELEMENTS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9deefd0b-b536-4779-9265-4d46c22ef500)
COMBINING & REPEATING LISTS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/bc8fc443-c280-4a7e-8aea-3d2a711c6fa2)
REMOVING LIST ELEMENTS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/146b2616-f63d-461d-b1c3-d34c864160b9)
LIST FUNCTION
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a2e1ae5c-b356-4866-ad1f-3dbed080fb08)
SORTING LISTS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2fc9f1e2-73db-4d56-a4ef-785030b9e977)
LIST METHODS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/566dbaee-e41c-4e61-a02f-6b573df403ce)
NESTED LISTS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fd3f793a-df8e-4f44-89cb-0f8ecbd1590b)
COPYING LIST
![image](https://github.com/Fuuko209/self-studied/assets/103474817/0513318e-5a9b-4ca0-8b4c-f6459b5b7f43)
.Copy()
![image](https://github.com/Fuuko209/self-studied/assets/103474817/db056b45-9ebc-483e-ae8b-f83ce4558b8d)
.Deepcopy()
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8f866dff-a9ff-4416-962f-88fd632cb234)

**TUPLES**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/df8f5233-801b-4072-b603-56686a23c856)
WHY USE TUPLES?
![image](https://github.com/Fuuko209/self-studied/assets/103474817/698ba5db-ebbb-46cd-9cf6-28bed716bf43)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a4916ec2-4453-40d7-81eb-2a8b72822bd8)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/27a3e626-1881-4f68-8196-f323c9dd73dc)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7a514a8d-edb8-439d-91df-0ebb85f41c74)

**RANGES**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/44ee14c1-fbd1-4786-9d1e-1a86d0ada0d7)

**LOOPS**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fac89d45-27d4-4beb-a52d-5c2f27cfd280)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/bf5b73e4-02c1-4ce5-93d4-fca4afd8c3d1)
PRO TIP :ENUMERATE
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8c55dac5-d011-416b-9067-ac72e5284956)

**WHILE LOOPS**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f0c5c448-fb1d-46a4-9505-bd9f5f533008)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fc2a8f4b-4946-4475-aaa9-424ce8e835d0)

**LOOP CONTROL**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/49ebe939-8f0b-4b39-a8a9-3efca13ebebb)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/796fa03e-9360-4070-a238-afc949368230)

**DICTIONARY**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/4e24d56f-ea3f-4951-ad40-b0395ad00cb7)
MODIFYING DICTIONARIES
![image](https://github.com/Fuuko209/self-studied/assets/103474817/876fcd25-6552-422c-8569-b78563776917)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/afc9a52c-e8a8-4fa2-ac79-fd8ea5c7e96c)
DICTIONARY METHODS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/780b3e05-0164-4087-86a0-843ba79787c4)
GET
![image](https://github.com/Fuuko209/self-studied/assets/103474817/aa73ee96-e6a5-43ce-a80f-5b206757a3e0)
UPDATE
![image](https://github.com/Fuuko209/self-studied/assets/103474817/5e235656-9f59-407a-b0e4-81d2b3c3fda9)
ZIP
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7947a042-8a7d-4c69-b3be-9bf6a7a46080)

**SETS**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/b41c09ec-8766-4afa-8eb4-0461b21847d1)
SET OPERATIONS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c9072ca5-c1f5-4091-b962-e5e44797d4da)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a682dd90-6522-42db-ba89-f19dc47b19ba)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c3c746ce-8f7f-4e65-b955-78eb180463e0)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7b100238-1c1c-458b-a212-d9af768c7a64)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6aa4c334-02eb-4309-b6bc-9937114f7fcb)
**DEFINING A FUNCTION**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/25b2bf2f-a25b-4b26-8e52-08897a635003)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2986f144-cf75-4b06-bc89-fd422ba37b51)
THE DOCSTRING
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7860e678-f6e8-4bed-ae3b-03606b989a93)
ARGUMENT TYPES
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6b23374a-48d3-4dc6-ac50-2dea0ca24b79)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1ad586b5-6aab-47c4-b731-6c1d7f602576)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9540ea3c-eec2-4263-905b-2318f04fc4f0)
VARIABLE SCOPE
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9cdae349-c132-4dc1-95d9-fd1fc9f78220)

CREATING MODULES
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1736cb9d-d305-4fff-b31e-8e1b8049bf73)
IMPORT MODULES
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1422f398-5e30-4752-92bd-36827a9ca315)

IMPORTING EXTERNAL FUNCTIONS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6b15a80e-8f58-464d-a0e4-a947c95ba98a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1c0d43ad-618f-4bf6-85c9-5247579640f6)

LAMBDA FUNCTIONS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/57dd42bd-ce72-4443-8631-d66646efc0da)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c013eb95-5e54-4339-b382-ae944d220671)

COMPREHENSIONS
![image](https://github.com/Fuuko209/self-studied/assets/103474817/eaa0acdb-f592-4d38-bd42-af69697125b3)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a796c6b1-ddbe-440f-9c96-14e4dc78dee5)

COMPREHENSIONS VS MAP
![image](https://github.com/Fuuko209/self-studied/assets/103474817/086b0182-4327-4809-8543-7811564a5749)

**MANIPULATING EXCEL SHEETS**

![image](https://github.com/Fuuko209/self-studied/assets/103474817/0fe3e62e-ccb6-4ad1-be8c-6228b2e62c2e)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/363246fc-29c1-4bfc-a6c9-23b0fd109086)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/28be0278-f66b-4575-99c1-b125cc32375b)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c11a27ac-2be6-49b1-8901-6b8d23307a48)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8a6147a7-12e9-443b-8ea9-51dd44a7e409)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/eff753c9-28f9-46d5-8367-ea62ead434c4)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/22db73ee-688a-4298-af1d-90922c87afd8)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/b65cb6aa-725d-4adc-8c56-2ac181535875)



### Numby
![image](https://github.com/Fuuko209/self-studied/assets/103474817/433fbf12-1771-4fe0-92c1-16b4e7cc96fe)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3ff94fa1-d5c8-4755-841a-45bfbe10c31c)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/88f38e71-fdfb-4c45-a5dd-33f3561b5f61)
Protip: Use T.shape to display colomn first and the rows are following.
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8a1ab2cf-aac1-4a7c-8a0c-35278f9533c1)

Array creation
![image](https://github.com/Fuuko209/self-studied/assets/103474817/edd19231-2b12-4d93-a2dc-1d66b5904cdb)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/6eb0f7ab-8a99-421c-b867-5370889b1156)

Indexing & Slicing Arrays
![image](https://github.com/Fuuko209/self-studied/assets/103474817/194a48e7-87b0-4d3f-ab7d-7d5ee34282b6)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/8707506b-685c-4562-8d39-643f2a09fda4)

Filtering Arrays
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e4a14405-0857-4a59-8289-3739356bc4ff)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/a3aaa1d6-1f85-42cf-aad0-155bbbff9b5a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/dbe700e6-d70c-4a91-9a6a-41adaf6a26a3)

Modyfying Array Values
![image](https://github.com/Fuuko209/self-studied/assets/103474817/478889c8-5a69-4e28-9b5d-8b213c9c37e4)

The Where Function
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e2523ba5-575a-4e7b-b63b-94d8fdcce012)

Array aggregation methods

![image](https://github.com/Fuuko209/self-studied/assets/103474817/ad8f2fbc-a0d0-46ec-a53b-36ab3f2b5e66)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/064608e8-0de1-49f8-b56f-96945758f33a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/911f406d-55c4-43ae-af1d-b4ab3ac337a5)

Array Function
![image](https://github.com/Fuuko209/self-studied/assets/103474817/556359f5-2958-4bb1-b054-4652aa4ecd61)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/6ae39deb-dac5-4d23-9185-e7da27eeade4)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/2f28b81a-f26f-4d32-8787-0196662eb007)

Vectorization

![image](https://github.com/Fuuko209/self-studied/assets/103474817/149bc86d-88aa-42ce-90b3-5a9dfc450030)

Broadcasting
![image](https://github.com/Fuuko209/self-studied/assets/103474817/96cc48e2-c7cc-479b-92b6-a3ac1a878efe)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/aeaf42ad-1a5a-491c-b0dc-3c3c92e0e086)



 ### Pandas
 ![image](https://github.com/Fuuko209/self-studied/assets/103474817/6479ef79-b9b7-45b7-88c0-13ff0821051b)
**Pandas series**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/5fa6b0ea-37fb-4305-8c10-e165c3544561)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8e544ce0-d84a-42ec-9297-1358ef575839)
**Pandas data types**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d174a894-ce7c-4b6b-9136-3941cf9ecb11)
**Type conversion**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/91a1a19b-f12c-401e-8b38-78dfe1821dab)

**Series Indexing**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/78d6192c-9362-43a6-a780-c430d9b2894e)

.iloc[]
![image](https://github.com/Fuuko209/self-studied/assets/103474817/115c440f-41d2-48b8-ae69-2d3acc108d4f)
.loc[]
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e3848894-d831-4f10-8851-cde78b794431)
Reseting the index
![image](https://github.com/Fuuko209/self-studied/assets/103474817/0d4056df-e539-4e7a-aace-7b02bd101024)
ex: my_series.reset_index(drop = True)
Fitering Series
![image](https://github.com/Fuuko209/self-studied/assets/103474817/28ab252c-44cc-499c-b780-cd5b93383965)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/66fd57c2-7ffc-4547-b22c-0fad109c7b0d)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1c445a3e-b749-42fa-bf46-49e097f5ffcf)
Sorting Series
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1c09397a-2465-457d-80a9-6957dd32bca7)
Arithmetic Operators & Methods
![image](https://github.com/Fuuko209/self-studied/assets/103474817/466c8842-b78c-4d7e-98cc-58f55b1083ea)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/77c67fd8-6241-41ae-a879-ed9ecb83b0e2)
Numeric Series Aggregation
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c1becbe8-348b-430e-9e78-7cdb553c4005)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2ad30ea7-71e4-43f8-9e0c-668eb0540a7d)
Categorical Series Aggregation
![image](https://github.com/Fuuko209/self-studied/assets/103474817/70f6d52f-786a-4028-8ad5-3ab2aaa91a06)
Missing Data
![image](https://github.com/Fuuko209/self-studied/assets/103474817/869f919d-1c03-4ce9-a947-b44818e118c5)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/43887224-e1a9-40d3-b1e1-fcdb941a3d56)
Check missing data
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7df1526f-75cd-4d9f-814c-9d522a3b4533)
Handling with missing data
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3004ab6f-e4a3-4652-b71d-4c7ee2afdf33)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/0e9085ab-0246-4102-ba2f-d1ed32a71cb0)

Apply() Method
![image](https://github.com/Fuuko209/self-studied/assets/103474817/42d7a3ba-7f64-4955-8f23-7dae04bcdb20)
Where() Method
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c1ad8e32-b068-4c04-9188-0a389868c031)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/38d7a5d7-5914-4a19-8ae9-91c1124d9e37)

### DataFrame
![image](https://github.com/Fuuko209/self-studied/assets/103474817/b7edf107-a812-48ad-8344-1eb90c63189f)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/02f158b8-e2be-4b60-b0fc-4f7d52141303)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e4f383ad-f451-4eae-bbb2-94988ad976de)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/bf0b779f-202e-426f-91df-8edfff85e73f)

Exploring a DataFrame
![image](https://github.com/Fuuko209/self-studied/assets/103474817/92c88fd4-9a99-4ff9-b8d8-f9115a38ef89)

Accessing DataFrame Columns
![image](https://github.com/Fuuko209/self-studied/assets/103474817/78bffad8-6561-4536-8a1b-75cc1d9bd611)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/b9070caa-7add-460e-aad5-ce68425cf284)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e826fb9a-fa3f-4450-b05c-d60247cb5099)

Accessing Data with iloc
![image](https://github.com/Fuuko209/self-studied/assets/103474817/59607ab2-7b28-43fe-ae96-e47b51496297)
Accessing Data with loc
![image](https://github.com/Fuuko209/self-studied/assets/103474817/01f73625-2ed9-4f3f-ba5d-b1c9d61a93af)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/95bceca2-8556-4a07-8f9d-b8d2599c34fc)

Dropping rows & columns
![image](https://github.com/Fuuko209/self-studied/assets/103474817/83d534c7-84e1-4dd6-96f6-b51497aebe64)

Indetifies duplicate rows
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fa09efd3-9ddb-45c1-8375-1f54b235e89b)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6c43703b-b10d-4654-bd11-2504b5d6ebe9)

Drop dublicate rows
![image](https://github.com/Fuuko209/self-studied/assets/103474817/911822c6-fd33-4d9b-af56-84ef0272b47b)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/85a7915e-9e7e-4417-93e8-de038bc123fb)

Missing data
![image](https://github.com/Fuuko209/self-studied/assets/103474817/82e8d336-22c4-4115-8d8d-f3fd61a09d43)
Handling with missing data
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6869f8dd-046a-4a17-8b9e-a853020b3ae7)
Filter Dataframe
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c68ae563-2a84-466e-8f90-762416ea32fe)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3367ec2f-a028-40b8-b17c-91a5ff559ce7)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a8474893-56e1-400e-87e7-b9c97e4f1e18)
Sort Dataframe
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1a1a0327-1452-44e4-bcf4-6366d321bd59)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/569c3a8c-887d-432c-a29e-8e6bed8e03bb)

Renaming Columns
![image](https://github.com/Fuuko209/self-studied/assets/103474817/93342346-997e-4602-ae0f-523e2cddb0c0)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a5782479-4319-4ba6-9b3d-c792a0919e20)

Reorder Columns
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1147ba4b-04cb-4983-8cc3-82821eea5504)

Arithmetric Columns Creation
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3f3a3360-cc75-4039-85e1-2b40cd2fb1c2)
Bolean Columns Creation
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fe4d3199-d56c-4ff6-b544-d6b45622ad1b)
Numpy Select
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6f967933-b19d-407f-a83b-de04a206930e)

Mapping Values To Columns
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fab49bb0-52a6-45af-a9ef-c9efd4eb6dac)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/614182e5-88ab-4d00-ad5b-1c16761f9a6c)

Column Creation With Assign
![image](https://github.com/Fuuko209/self-studied/assets/103474817/604ddea0-ef3c-496a-b52a-766b587765f8)

**Pandas Data Types**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d5e44372-09d6-4152-8011-47a0ec9e0f57)
The categorical Data Type
![image](https://github.com/Fuuko209/self-studied/assets/103474817/531b9dda-0e47-4c1f-bfd0-e5c4c1025f89)

Type Conversion
![image](https://github.com/Fuuko209/self-studied/assets/103474817/45f72b91-6f91-4105-a008-844802448c68)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/bfa5ab2f-bb5f-4f94-88b5-03502c2c32c5)

**Memory Optimization**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a2661e47-b1e1-47da-af85-bf12f87909d1)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/76ba4e8d-cb13-40d0-ad8b-3c067888b3fc)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c437c12b-d5fb-469c-ab84-c19ca5a8453b)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/b5d747a3-7288-4273-b15c-67655ac475c9)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d831cc4c-8c4d-4f9b-8bc4-794264df2d7c)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/08ae6884-4747-4fa3-a1f3-5df77e453372)

## Aggregating & Reshaping Dataframes
**Aggregating Dataframes**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1fbede8d-50a2-4a59-8f68-d6cabe9d9495)

**Grouping a Dataframe**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/dfe92133-df96-4917-8ba7-fcf7a282170b)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/123f1ed0-0666-4b19-91e6-a58d8daaadc7)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2e2e569b-6106-485f-973c-84389ba207f3)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/bf7311a7-b307-423e-84be-a4f0bf4004e1)

**Multi-index Dataframes**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/28b0e887-5873-4c00-ad81-8020f86e519c)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/248d3b8b-5d50-4981-ae78-936baa8a87e3)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/ef1c9b3e-a59e-4891-abe4-13d110b2459e)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c4fbd3ef-9762-4aaa-b193-3aa7d1f81289)

**Aggregating Groups**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d91b2dde-ccf8-4379-be11-c7acd0ad6c0f)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/15251884-5240-49e1-a703-db9a5f7e1d4a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/af1d56a2-3e75-4f78-880d-3cf2c914eb63)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f5b3f7e4-4c65-483b-bde9-e67bf4e1d54f)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1368bc7e-c11b-4f1f-8c78-84e7f202592c)

**Pivot Tables**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d2a524ba-aa5a-4531-a171-e61330dc3daa)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/76b21aed-940e-4b08-a98b-9bfcf60f742a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/a3a5ba3a-d10f-4455-b2d1-421526dac01a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/ff1010c1-ba70-4c84-a1f9-bb20a79bb5a6)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/5e88ab2b-df4c-4f01-b648-0d9c81a7913a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/78a7e50e-eafe-49cc-b9df-260d44e68233)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/5b35c6c0-b483-4891-a44a-56d38afcf183)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c2c21a6f-bb69-4ba4-8778-d9e6f6bcf202)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/70af8f60-c45a-436d-a7cf-8a2bce52dbca)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/1b3aa9eb-113c-4bb7-bc4e-53caaf1c2039)




# Power Platform
Power Apps components
| Power Apps Home Page | Power Apps Mobile | Power Apps Admin Center |
|---|---|---|

### Way to build Power App
1. Create an app from a template
2. Create an app from a data source
3. Build from a blank canvas

### Build a mobile-optimized app from Power Apps**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/5d4406a2-c588-4310-94cb-c030a2b6f933)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/895f76c9-ed20-45fa-bab3-428849d6f809)
https://learn.microsoft.com/en-gb/training/modules/build-mobile-optimized/components
**Identify performance considerations for a mobile-optimized canvas app**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/77c6708b-a64e-47d9-9835-3ef5372fc6de)

### Power Automate
![image](https://github.com/Fuuko209/self-studied/assets/103474817/6b5f3e46-ca36-457b-b917-1cfed75dfd14)

# Analytical Thinking

### Type of Data
![image](https://github.com/Fuuko209/self-studied/assets/103474817/88052054-94e4-4dfa-b882-ee597160b66b)

### What can data do
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f9962cf2-5095-4c00-8164-8dc20706b589)

### How enterprise can do with data?
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9388a8e4-4844-44b5-998e-eabe8a0efaa0)

### What are the four types of data analytics?
![image](https://github.com/Fuuko209/self-studied/assets/103474817/4d57da5c-7c1e-4141-837f-a086002dc7a5)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/4b84c077-0908-407c-ba6a-9a7947d83467)

### What kind of dashboard and report?
![image](https://github.com/Fuuko209/self-studied/assets/103474817/27efa9a3-8937-4cda-8d1c-a047d1956360)


# Digital Marketing and E Commerce
### Digital marketing advantages
| Reduces wasteful spending | Adapts to new technologies | Reaches target audiences with more precision |
|---|---|---|
| Digital marketing uses content in a variety of formats that can be easily converted from one format to another, making spending more cost-effective | When marketers receive data faster, they’re able to change direction easily if a marketing effort isn’t producing the results expected. Measuring the success of digital marketing campaigns is key to ensuring that you get the results you want. | Ad visibility and audience coverage can be tailored to meet your specific business needs and goals. | 
| **Advantage**: Digital content is easier to create. |**Advantage**: Digital marketing adapts to new technologies. |**Advantage**: Digital marketing adapts to new technologies. | **Advantage**:Digital marketing tools expand customer reach using specific audiences. |
| **Challenge**: the integration or synchronization of content on multiple channels—so customers can have a consistent brand experience. This increases the amount of content required, so even if it’s easier to create digital content, much more content needs to be created overall | **Challenge**: Marketers must also stay up-to-date with and follow all user privacy and data sharing regulations worldwide. | **Challenge**: The digital space is a crowded field that’s getting even more crowded. It’s harder for marketers to stand out with their advertising, even when they are targeting the right audiences. |
| **Advantage**: Digital marketing is more cost-effective than traditional marketing.|
| **Challenge**:  Getting support or buy-in for extra or additional budget to cover the cost can be difficult. |

### Inclusive markeing

**Making inclusive choices and avoiding stereotypes**
Here is a list of some identity traits that are helpful to keep in mind when you’re creating marketing or advertising materials for the people you’re trying to reach

Race

Socioeconomic status

Age

Ability

Gender

Sexual orientation

Religion

Geographic location

Culture

Political perspective

Military status

Languages spoken

As an example, at least one billion people in the world live with a disability. If your product or service isn’t accessible to these people, they likely don’t use or even know about your product or service. And if your company’s marketing efforts don’t feature people with disabilities or address their needs, they may not view your company’s products or services as relevant to them.

**The customer journey**: The path a customer takes from learning about a product to getting questions answered to making a purchase.
**Customer journey map**: A visualization of the touchpoints a typical customer encounters along their purchase journey.
![image](https://github.com/Fuuko209/self-studied/assets/103474817/82e37548-c0ec-40b3-9ae8-43317a5bfb92)


**The marketing funnel**: A vissual representation of the process through which people go from fist learning about a brand to becoming loyal customers.
![image](https://github.com/Fuuko209/self-studied/assets/103474817/79930b7d-cc70-4973-9505-1380221b61d7)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2fe9467e-bf99-4244-b104-ae0ea394534b)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/c6d7e2aa-a73e-434e-b14f-7220c81e37b1)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/63b3527a-4192-4d6f-8a1f-b2ff7cc0bba9)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c5d2965e-0289-4fd8-82ea-8ba31deb5ab1)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/94224059-89e6-4de5-859c-f8f4fb6ca22f)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/84a1a597-5975-4c03-9c95-c0672b53104c)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/fc50c5b8-932c-494d-9f0d-581557988657)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/33067060-2be1-486d-94d7-2162721d1ce8)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7c605615-356a-439e-9cab-10609e666ac3)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9cd88ba3-409f-4e8b-98f0-e6907c3d9f32)

**Awareness tactics**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/950a3ab6-206a-49ad-88f0-d378572ad22b)
**Messuring awareness**: A digital marketer can measure the awareness of their ads by tracking Impressions, Reach, Frequency


**Consideration tactics**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e9a0c5c1-d2fa-4b83-96c2-10068a037084)

**Measuring considerations**: 
1. How often customers search for your business online?
2. Number of first-time visitor
3. Number of pages per visitor
4. How long visitors spend on a page
5. Email or newsletter signup
**Conversion tactics**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7c326ab0-01c9-4a5f-9af8-e7f8ca7be351)

**Measuring conversion**
1. The number of converion
2. Time to conversion
3. Cost per conversion
4.  Average number of touchpoints
5. Average order size
   
**Loyal tactics**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3a2f6ba4-2c4c-4a6b-bf21-74def005bcc5)

**Measuring loyalty**
1. Rate of repeat purchases
2. Length of time between purchases
3. Number of orders per customer
4. Rate of account activation after sign-up
5. Engagement with rewards programs.

**The future of e-commerce**

1. Specialization ò smaller retailers.
2. Immersive customer experiences
    + Virtual reality (VR)
    + Augmented reality (AR)
    + Chatbots
4. Distribution and delivery innovations

**Business Goals:** focused on desired aims, achievements, or outcomes for a business. Business goals typically include things like: increasing profits, gaining new customers, improving customer service, raising productivity, or launching new products or services.
**Marketing Goals:** focused on specific objectives in a marketing plan or strategy that should support a business's larger aims. Marketing goals typically include things like: raising brand awareness, increasing web traffic, generating new leads, and driving sales or conversions.

![image](https://github.com/Fuuko209/self-studied/assets/103474817/207d619a-1613-46b4-8145-92391f0d133e)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/56fb4f54-b1c5-4c50-af2b-15a3801fadca)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/afc65732-7f55-470e-9c77-f939aaf3e4b9)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8147480a-ee9b-4acb-aa65-6c7e8a396a05)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2c710365-bda9-4949-a8ed-faeced53ee7f)

**SEO** Search engine optization: A set of practices designed to increase the quanity and quality of trafic to website
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d9b229cb-96be-465d-9bec-51fde02b6cc5)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/f5fa7619-ff6c-4a35-8d64-11ef5932ec64)

**SERPS** Search engine result pages: produced when someone performs a search
![image](https://github.com/Fuuko209/self-studied/assets/103474817/06f83264-efb6-4039-9ec4-2e67b17ec0e1)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9683ee2b-900e-4337-94a4-c90764dd222f)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/22cb4dae-8fa1-4d82-a232-0a39cb767a43)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2dc6bb15-6df5-40da-a1ed-a33368ecc56f)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/165bf3aa-2c32-47db-b434-74f67271abfe)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/0f7717d0-bd24-4406-a009-e71a61e80472)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/681952b1-2740-4d20-9828-2e7ca6d1d960)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e025584f-8855-4484-b793-b8b9f66d48b8)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/35e3bf33-3567-45be-b8ae-2c6d168ce67a)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/4d303e1d-1e86-4520-93b9-36f0b5f95d57)

**Build relationships with email marketing:**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/adc1c9ce-0186-4388-bd76-30488483975f)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/421a68d9-e83c-4a5c-bbbb-4ddbe3609334)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/eb7a8661-c1e3-448c-854c-6f920887c532)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/4d032c48-b63b-4a13-94cb-65dfc74a8a6a)

**Attribution models for digital marketing**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/03b2015a-9066-4f9d-8185-83be755c15e6)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f026ec91-5a82-4950-a631-8f3a5f9d71db)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/2b81f710-6e34-4367-aa8f-4b5ad5d3c3f3)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/9610e190-d655-4856-a012-13a533838ef5)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/93e433ec-9273-447a-96fa-3f2dbf26bdc3)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e7984718-700f-4216-b662-1c3e52b2e1ec)

**Data storytelling**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/e6eea539-5b87-4cd5-9608-7101a473df28)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/4b96fa72-dcfd-43ac-b90a-c30963ccc35c)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/8115574e-b3d3-4d1c-9b3c-3491e6188c48)
![image](https://github.com/Fuuko209/self-studied/assets/103474817/d8880ec7-b913-4799-bb65-82ac64579639)

**Create customer personas for your target audience**


![image](https://github.com/Fuuko209/self-studied/assets/103474817/eb529701-3f37-4105-b0c5-01695102bb54)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/874f359a-2dce-4e69-97f5-487cc8237697)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/a08b000c-3d72-439e-a2fa-86b4a2cef741)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/cfc97f6c-be5b-4f06-a04b-3285dd29e5eb)


**Consideration: Strategies to build interest in your product or service**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c733993b-fa9b-4a11-887a-ff66d3cb2573)

**Conversion: Stategies to increase the conversion rate on a website**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/507436fd-f8d1-4559-bf8c-4207e660c9f9)

**Loyalty: Strategies to increase th loyalty of customers after a purchase**
![image](https://github.com/Fuuko209/self-studied/assets/103474817/3d719756-05dc-4a72-9570-cf39ccbbde28)



# Google UX Design

 For a user to have a good experience, the product needs to be:
![image](https://github.com/Fuuko209/self-studied/assets/103474817/7c0bf262-c8d8-4ba4-b841-7343f9f5c371)


![image](https://github.com/Fuuko209/self-studied/assets/103474817/b4da6d53-1474-4e6b-8512-2fa7b5b23abc)



