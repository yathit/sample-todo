sample-todo
===========

YDN-DB javascript database library is abstraction layer for multiple storage mechanisms, including IndexedDB, Web SQL database and WebStorage (localStorage). On top of that, ydn-db provides ORM like query capability.

The first thing you need to think using database is its schema. A database in IndexedDB, and hence YDN-DB, are composed of several Object Stores. You will create an object store for each type of data. Each Object Store can have a collection of Indexes that make it efficient to query and iterate across. Being key-document store, there is no relationship between object stores.

This sample application code demonstrate very simple use case of ynd-db library to build todo list manager.
