# CREATE DATABASE

![image](https://github.com/asyikin22/MySQL/assets/148519441/a2b39b93-d364-4e90-9817-398c772100a9)

**How to use the right database?**
- right click
- Write USE statement <DB name> semi-colon

![image](https://github.com/asyikin22/MySQL/assets/148519441/62b90359-02b5-4b6c-9388-2a80da098449)

**How to DROP (delete) database?**

![image](https://github.com/asyikin22/MySQL/assets/148519441/cd01a90e-9862-4daa-aa22-2414785ceefb)

# CREATE TABLE

**CREATE TABLE**
- Create column
- Set the data type for the column.

![image](https://github.com/asyikin22/MySQL/assets/148519441/66824631-3d28-4d06-b274-8fe57f00f78b)

**ALTER TABLE**
- Add phone number
- ALTER TABLE 'DB name'
- Add 'new column';
- To view new table - SELECT * FROM <DB name>

**RENAME COLUMN**
- ALTER TABLE employees
- RENAME COLUMN phone_number TO email; ---> EXECUTE
- To view new table - SELECT * FROM 'DB name'
  
![image](https://github.com/asyikin22/MySQL/assets/148519441/20a3f30f-9ad8-4907-8239-d3a3a7198855)

**MODIFY COLUMN**
- Change number of character for email
- ALTER TABLE employees
- MODIFY COLUMN email VARCHAR(100);  ---> EXECUTE

![image](https://github.com/asyikin22/MySQL/assets/148519441/da7bd136-e515-4ea9-a979-5d30cd0fa34e)

**MODIFY COLUMN**
- Move email to be next to hourly_pay column
- ALTER TABLE employees
- MODIFY email VARCHAR(100)
- AFTER hourly_pay; ---> EXECUTE

![image](https://github.com/asyikin22/MySQL/assets/148519441/8f30f0a1-ea66-462b-a0ec-5cea61941359)

**DELETE COLUMN**
* ALTER TABLE
* DROP COLUMN email  ---> EXECUTE

# INSERT ROWS INTO TABLE

**ENTER A SINGLE DATA**
- INSERT INTO employees
- VALUES (1, "Nur", "Asyikin", 40.00, "2024-01-01" ); ---> EXECUTE
- Make sure you have the right data type for each column

![image](https://github.com/asyikin22/MySQL/assets/148519441/4d9a778d-e338-4466-9e37-34c0802eb0ad)

**ENTER MULTIPLE ROW OF DATA AT ONCE**
- Set up multiple parentheses for values

![image](https://github.com/asyikin22/MySQL/assets/148519441/7869e57a-2a71-426a-919a-344fc36681fd)


**ENTER DATA WITH INCOMPLETE INFORMATION**

![image](https://github.com/asyikin22/MySQL/assets/148519441/5f6eaab0-62e4-4fa2-b7cb-c1558ba6c890)

**SELECT DATA FROM TABLE**

![image](https://github.com/asyikin22/MySQL/assets/148519441/9db56ca4-8697-4d33-8517-c83c8d1219c3)

# UPDATE & DELETE DATA FROM TABLE

* How to disable safe mode to update and delete: https://youtu.be/gkTmTp_Swl8

![image](https://github.com/asyikin22/MySQL/assets/148519441/c98eecbb-216f-4284-9f5c-cd81c90bbab6)

# AUTOCOMMIT, COMMIT, ROLLBACK

![image](https://github.com/asyikin22/MySQL/assets/148519441/31efb308-f4ac-4301-b1c2-90767bdedff4)

# CURRENT DATE AND TIME

![image](https://github.com/asyikin22/MySQL/assets/148519441/c3f40ca4-dccf-445a-b9c1-4035ab3d3d10)


# UNIQUE CONSTRAINT

![image](https://github.com/asyikin22/MySQL/assets/148519441/8136888d-19d1-4b3a-8b68-3d3df5e3a106)

# NOT NULL CONSTRAINT

![image](https://github.com/asyikin22/MySQL/assets/148519441/cf5ea5d8-e43b-4c52-95a6-4aacacc84fb3)

# CHECK CONSTRAINT

![image](https://github.com/asyikin22/MySQL/assets/148519441/359227a8-0bcb-422a-a42e-f783dd5806c9)


# DEFAULT CONSTRAINT

![image](https://github.com/asyikin22/MySQL/assets/148519441/3ca32968-1e65-421a-8714-8e1e2fa1c5d2)

# PRIMARY KEY

![image](https://github.com/asyikin22/MySQL/assets/148519441/0eb554e2-caa3-4005-8ec4-dd51f39a62ea)

# AUTO INCREMENT

![image](https://github.com/asyikin22/MySQL/assets/148519441/b96cbd22-dc26-497c-bf4e-8e3c8f823d76)

# FOREIGN KEY

![image](https://github.com/asyikin22/MySQL/assets/148519441/2b3812fd-aad0-42c2-88d9-53cd116640ad)








