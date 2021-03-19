# WordNet 3.0, version for SQL Server 2005, with views, functions, and stored procedures

This is an MS-SQL database containing WordNet 3.0 that supports [this WordNet GUI editor](https://github.com/GregWickham/WordNet_GUI), written for WPF.

It's based on the MS-SQL database created by Michal Měchura:

https://github.com/michmech/wordnet-mssql

The database schema has been extensively reworked, some table rows have been removed (but the original data is all there), and I've added a number of views, stored procedures, and functions.

The views are intended to make it easier to explore the contents of WordNet.

The functions and stored procedures support [the WordNet editor.](https://github.com/GregWickham/WordNet_GUI)
