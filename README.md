## Table of Contents
- [SQL](#sql)
- [Python](#python)
- [Power BI](#power-bi)
- [Power Platform](#power-platform)
- [Analytical Thinking](#analytical-thinking)
- [Digital Marketing and E Commerce]. (#digital-marketing-and-e-commerce}

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

### Data Type
![image](https://github.com/Fuuko209/self-studied/assets/103474817/f11f3211-b2ff-4b6a-8e1b-529e185199a9)
 USE TYPE FUNCTION TO DETECT DATA TYPE
![image](https://github.com/Fuuko209/self-studied/assets/103474817/c626686f-2b9b-4030-9ac1-8007da1500b0)
USE TYOE CONVERSION
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


# Power Platform
Power Apps components
| Power Apps Home Page | Power Apps Mobile | Power Apps Admin Center |
|---|---|---|

### Way to build Power App
1. Create an app from a template
2. Create an app from a data source
3. Build from a blank canvas





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
Digital marketing advantages
| Reduces wasteful spending | Adapts to new technologies | Reaches target audiences with more precision |
|---|---|---|
| Digital marketing uses content in a variety of formats that can be easily converted from one format to another, making spending more cost-effective | When marketers receive data faster, they’re able to change direction easily if a marketing effort isn’t producing the results expected. Measuring the success of digital marketing campaigns is key to ensuring that you get the results you want. | Ad visibility and audience coverage can be tailored to meet your specific business needs and goals. | 
| **Advantage**: Digital content is easier to create. |**Advantage**: Digital marketing adapts to new technologies. |**Advantage**: Digital marketing adapts to new technologies. | **Advantage**:Digital marketing tools expand customer reach using specific audiences. |
| **Challenge**: the integration or synchronization of content on multiple channels—so customers can have a consistent brand experience. This increases the amount of content required, so even if it’s easier to create digital content, much more content needs to be created overall | **Challenge**: Marketers must also stay up-to-date with and follow all user privacy and data sharing regulations worldwide. | **Challenge**: The digital space is a crowded field that’s getting even more crowded. It’s harder for marketers to stand out with their advertising, even when they are targeting the right audiences. |
| **Advantage**: Digital marketing is more cost-effective than traditional marketing.|
| **Challenge**:  Getting support or buy-in for extra or additional budget to cover the cost can be difficult. |







