# freeCodeCamp Relational Database – Coursework

Workshops completed as part of the freeCodeCamp Relational Database curriculum, covering Bash, shell scripting, SQL, PostgreSQL, Git and nano.

## Workshops

| Folder | Workshop | Topics |
|---|---|---|
| `bash-boilerplate` | Learn Bash by Building a Boilerplate | Terminal navigation, creating/moving/deleting files and folders |
| `sql-mario-database` | Learn Relational Databases by Building a Database of Video Game Characters | Tables, data types, primary/foreign keys, one-to-one, one-to-many and many-to-many relationships, joins |
| `bash-five-programs` | Learn Bash Scripting by Building Five Programs | Variables, arguments, loops, conditions, arrays, user input, random numbers |
| `sql-student-database` | Learn SQL by Building a Student Database (Parts 1 & 2) | Creating tables, foreign keys, importing CSV data with Bash, SQL queries and joins |
| `bash-kitty-ipsum-translator` | Learn Advanced Bash by Building a Kitty Ipsum Translator | Piping, redirecting input/output/errors, grep, sed, wc, regular expressions |
| `bash-sql-bike-rental-shop` | Learn Bash and SQL by Building a Bike Rental Shop | Interactive menus, functions, input validation, SQL inserts and updates from a Bash script |
| `nano-castle` | Learn Nano by Building a Castle | Editing files in the terminal with the nano text editor |
| `git-sql-reference` | Learn Git by Building an SQL Reference Object | Branches, merging, resolving conflicts, rebasing, stashing, .gitignore (commit history in git-history.txt) |

## What I learned

### Command line & Bash

- Navigating the file system and managing files and folders from the terminal
- Writing Bash scripts with variables, arguments, conditions, loops, functions and arrays
- Reading user input and validating it with regular expressions
- Redirecting input, output and errors, and chaining commands with pipes
- Processing text with `grep`, `sed` and `wc`
- Editing files directly in the terminal with nano

### SQL & PostgreSQL

- Designing relational databases with primary and foreign keys
- Modelling one-to-one, one-to-many and many-to-many relationships, including junction tables
- Creating, altering and deleting tables and columns
- Inserting, updating and deleting data
- Querying data with filters, sorting, aggregate functions and joins
- Importing CSV data into a database with a Bash script
- Running SQL queries from inside Bash scripts to build interactive programs
- Saving and restoring databases with `pg_dump`

### Git

- Initialising repositories and making commits
- Creating, switching and merging branches
- Resolving merge conflicts
- Rebasing, stashing and reverting changes
- Keeping sensitive files out of a repository with `.gitignore`

## How to run

Bash scripts can be run from their folder after giving them executable permissions:

```bash
chmod +x script_name.sh
./script_name.sh
```

Folders that include a `.sql` file contain a database dump. The database can be rebuilt with:

```bash
psql -U postgres < file_name.sql
```

Scripts that use a database expect it to exist locally in PostgreSQL.
