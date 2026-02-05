#This project is a relational database named universe that models astronomical data, developed as part of my computer science curriculum. It focuses on architecting a complex schema and maintaining data integrity using PostgreSQL.

##Project Overview
The goal was to build a structured database from scratch to map galaxies, stars, planets, and moons while meeting strict relational constraints.

Relational Schema: Designed a database with five normalized tables: galaxy, star, planet, moon, and a custom table for additional data.

Data Integrity: Implemented auto-incrementing Primary Keys and linked tables through Foreign Keys to establish clear one-to-many relationships.

Constraint Enforcement: Enforced strict data standards using UNIQUE, NOT NULL, and specific data types like INT, NUMERIC, and BOOLEAN.

Environment & Admin: Developed using GitHub Codespaces and managed database version control via Bash terminal utilities, including psql and pg_dump.
