# ghactions-db

A SQLite3 database, integrated with GitHub Actions.

This is kind of a bad idea, but it seems pretty fun!

## How to use:

Create an issue with any title you'd like and a SQL query in its body. For example:

```
Title: Hello World
Body: SELECT * FROM mytable
```

Make sure to escape quotes (similar to running commands through the command line), ex.

```
INSERT INTO mytable (messages) VALUES (\"Hello there\")
```

GitHub actions will execute the query and you'll get a reply with a link to your output file!

Have fun!

