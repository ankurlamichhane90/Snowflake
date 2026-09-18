# Snowflake

Lecture notes and hands-on practice from the Snowflake module of the Codebasics Data Engineering Bootcamp.

Everything here is written and run inside a Snowflake Workspace and pushed straight to this repo from Snowflake. There is no local copy.

## Environment

- Database: SNOWFLAKE_LEARNING_DB
- Schema: ANKURLAMICHHANE11_LOAD_SAMPLE_DATA_FROM_S3
- Workspace: Snowflake_Git, connected to this repo on main

## Progress

### 1. Load sample data from AWS S3

Folder: Load sample data from AWS S3 with SQL

Loaded a sample menu dataset from a public S3 bucket into a Snowflake table with SQL instead of the point and click loader.

Notes:

- add your notes here

### Next up

- next topic

## Repo files

- README.md, this file
- snowflake_learning_db_ddl.sql, a snapshot of the object definitions in SNOWFLAKE_LEARNING_DB
- Load sample data from AWS S3 with SQL, the folder holding the S3 loading exercise

Regenerate the DDL snapshot any time with:

SELECT GET_DDL('DATABASE', 'SNOWFLAKE_LEARNING_DB', TRUE);

## Working on this repo

Open the Snowflake_Git workspace in Snowflake, pull, make changes, then push from the Changes tab. Pull first if anything changed on GitHub, so you do not hit a conflict.
