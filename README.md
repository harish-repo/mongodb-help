# Basic Commands
Connect to local host on default port 27017

    mongo

Connect to remote host on specified port

    mongo --host <hostname or ip address> --port <port no>

> mongo --host 10.121.65.23 --port 23020

Connect to a database

    mongo <host>/<database>

> mongo 10.121.65.58/mydb

Show current database

    db
Select or switch database

    use <database name>

> use mydb

Execute a JavaScript file

    load(<filename>)

> load (myscript.js)

Display help

    help

Display help on DB methods

    db.help()

Display help on Collection

    db.mycol.help()


 ## Show Commands
Show all databases

    show dbs

Show all collections in current database

    show collections

Show all users on current database

    show users

Show all roles on current database

    show roles

