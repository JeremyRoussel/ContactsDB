# ContactsDB
Basic Contacts Database with 4 API Endpoints for CRUD operations

This Express Server hosts a local API for storing contact information.

To use, enter the following commands after cloning:

1. Install dependencies with npm: contactsDB ~ npm install
2. Create database with PostgreSQL: ~ createdb contactsapp
3. Create table with pSequel:

CREATE TABLE contacts (
 id serial PRIMARY KEY,
 first VARCHAR(100),
 last VARCHAR(100),
 email text UNIQUE NOT NULL,
 phone VARCHAR(100),
 location VARCHAR(100),
 hobby VARCHAR(100),
 added TIMESTAMP NOT NULL
);

4. Start Server: contactsDB ~ npm start

Clone the front-end application and run it as well.

Front-End Repository location: 
