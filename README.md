# Music Library Management System

This repository contains SQL files for the **Music Library Management System** project. The system is designed to manage a collection of music data, including albums, artists, playlists, songs, and user accounts. This project demonstrates database design, data manipulation, and complex queries to interact with a music library.

## Project Overview

The Music Library Management System is structured to allow users to:
- Store and retrieve information about albums, artists, playlists, and songs.
- Manage user playlists and playlist songs.
- Support various operations, including advanced queries, indexing, and transaction control.

## Folder Structure and SQL Files

1. **ddl-commands.sql**: Contains Data Definition Language (DDL) commands for creating the tables and database schema for the system. It includes definitions for tables like `albums`, `artists`, `songs`, `playlists`, and `users`.

2. **dml-commands.sql**: Contains Data Manipulation Language (DML) commands to insert sample data into the tables. This data can be used for testing and verifying the database setup.

3. **indexing-query.sql**: Creates indexes on key columns to optimize query performance within the music library system.

4. **advanced-queries.sql**: Contains complex SQL queries for retrieving insights from the music library, such as:
   - Finding popular songs or albums.
   - Fetching songs by a specific artist.
   - Retrieving playlists and their associated songs.

5. **tcl-commands.sql**: Includes Transaction Control Language (TCL) commands like `COMMIT` and `ROLLBACK` to manage transactions and ensure data consistency.

## How to Run

1. **Set Up MySQL**:
   - Install MySQL on your system if it’s not already installed.
   - Start MySQL and create a new database for the project:
     ```sql
     CREATE DATABASE music_library;
     USE music_library;
     ```

2. **Execute SQL Scripts**:
   - Clone this repository and navigate to the folder where you saved the SQL files.
   - Open each file in order and run the commands using MySQL:
     ```sql
     SOURCE path/to/ddl-commands.sql;
     SOURCE path/to/dml-commands.sql;
     SOURCE path/to/indexing-query.sql;
     SOURCE path/to/advanced-queries.sql;
     SOURCE path/to/tcl-commands.sql;
     ```

3. **Verify Setup**:
   - Use `SHOW TABLES;` to ensure tables are created.
   - Run sample queries to verify that data is inserted and accessible.

## Project Goals

This project aims to showcase:
- Database schema design for a music management system.
- Use of DDL and DML commands for setup and data insertion.
- Optimization using indexing.
- Use of TCL commands to manage transactions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
