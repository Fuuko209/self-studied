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
























**Primary Key & Foreign Key**
| Primary key | Foreign key |
|---|---|
| Primary key is a column used to uniquely identify rows in a table. It is required to have a unique value (UNIQUE) and cannot contain NULL values. A table can have only one primary key.|Foreign key is a column used to reference another table by linking it to the primary key of that table.|
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/235f920b-5130-4d01-a1b5-7c1bbb6dab4f) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/d343bc29-8c0d-4bae-bad8-2ff89c192871) |
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/b635c154-0964-48ff-9e9d-1eb3d69c0acb) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/64f5fdbb-2579-41fa-a4a6-541321d45d2c) |
| ![image](https://github.com/Fuuko209/self-studied/assets/103474817/f7beffcf-573a-4817-94c4-0ed793a181b4) | ![image](https://github.com/Fuuko209/self-studied/assets/103474817/480ec3b2-bea6-443f-b857-753900766b49) |

**The relationships** between tables in a relational database are commonly classified into three types: One-to-One (1:1), One-to-Many(1:N), Many-to-Many (N:M)

![image](https://github.com/Fuuko209/self-studied/assets/103474817/65a4befb-764e-42cd-802d-ee7fdf1bfe5e)





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












