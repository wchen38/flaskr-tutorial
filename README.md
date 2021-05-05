# to access the sqlite database
1. run the command ‘sqlite3’ inside directory that contain the database
2. By default a “transient in-memory database” is opened. You can change the    database by use of the .open command. (eg: .open flaskr.sqlite)
3. use '.table' to show all the table in the database
4. use 'select * from user' to select user column in the table