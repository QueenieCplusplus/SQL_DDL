# SQL DDL
Data Defined Language

可建立、刪除、更新資料庫中的物件，主要是給管理者使用的命令。

通常要建立物件時，使用語法如下：

* 建立 Create XXX

  在建立物件時，倘若資料庫中已有同名物件存在，便會回傳錯誤，故可用
  
  * Create Table If Not Exists foo

* 刪除 Drop XXX

* 更改屬性 Alter XXX

此指令是用來建立或是刪除資料庫中的資料表或是 View 等資料庫物件，其他物件包含 Trigger 以及 Procedure。

# MySQL 為例

* Create Table

* Create Table As

* Create Temporary Table 

* Drop Trable

* Alter Table

* Truncate Table

* Create Index

* Create View

* Drop View

* Create Procedure

* Drop Procedure

* Create Function

* Drop Function

* Create Trigger

  * 屬性包含 timing 和 event。
  
* Drop Trigger

* Create User

* Drop User

* Grant

# Oracle 為例

* Create Cluster 

* Drop Cluster

* Create Package

  * package 為 procedure ｜ function 的集合體。

* Drop Package

* Create Package Body

* Create Synonym

* Drop Synonym

# PostgreSQL 為例

* Cluster

* Create Event Trigger

* Create Sequence

* Drop Sequence

# DB2 為例

* Create Alias

* Drop Alias

# SQL Server 為例

* sp_addlogin Create Login

  建立可登入使用者

* sp_droplogin Drop Login

  刪除可登入使用者
  
* sp_grantdbaccess Create User

  能執行此指令的角色，僅限於 sysadmin 或是 securityadmin。

* sp_revokedbaccess Drop User

  能執行此指令的角色，僅限於 sysadmin 或是 securityadmin。

