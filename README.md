# WordNet 3.0 for Microsoft SQL Server, with views, functions, and stored procedures

This is an MS-SQL database containing WordNet 3.0, supporting [this WordNet GUI editor](https://github.com/GregWickham/WordNet_GUI) written for WPF.  The .zip file contains an MDF file that you can attach in SQL Server.

It's based on the MS-SQL database created by Michal Měchura:

https://github.com/michmech/wordnet-mssql

The database schema has been extensively reworked, some table rows have been removed (but the original data is all there), and I've added a number of views, stored procedures, and functions.

The views are intended to make it easier to explore the contents of WordNet.

The functions and stored procedures support [the WordNet editor.](https://github.com/GregWickham/WordNet_GUI)

The database defines a user named WordNetEditor, which has read / write / execute privileges on all the database objects needed by the WPF editor.  The simplest way to get the editor running is probably to create a login on your SQL Server instance that corresponds to this user.
