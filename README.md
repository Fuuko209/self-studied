## Table of Contents
- [SQL](#sql)
- [Python](#python)
- [Power BI](#power-bi)
- [Power Platform](#power-platform)
- [Analytical Thinking](#analytical-thinking)

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
![image](https://github.com/Fuuko209/self-studied/assets/103474817/ce06a51d-c690-4cad-abb9-781a92ea5d38)
Lower Bound needs to be placed BEFORE the Upper Bound
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












