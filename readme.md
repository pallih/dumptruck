Highwall is an document-like interface to an SQLite database that lets you relax.
It supports the following database formats.

Quick start
---------
Highwall makes relational databases feel more like document databases.

## Saving
The simplest `save` call looks like this.

    save({"firstname":"Thomas","lastname":"Levine"})

This saves a new row with "Thomas" in the "firstname" column and
"Levine" in the "lastname" column. It uses the table "default" inside
the database "default.db".

Generic functions
-----------
Highwall gives you eight functions.

These two are the coolest.

* `save`: Save to the database in a relaxing manner.
* `select`: Select from the database in a relaxing manner.

These two make it easy to save individual variables.

* `get_var`
* `save_var`

Here are some wrappers for common commands.

* `show_tables`
* `drop`: Delete a particular table.

These two let you run normal SQL.

* `execute`: Run raw SQL commands.
* `commit`: Commit SQL commands