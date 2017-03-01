Assignment Details:
https://github.com/LukeSchlangen/phi-pg-module-intro

Node SQL Form Update:

Expand upon the form and database from lecture.

Get code from Github
NOTE: If you have the code from lecture, just start from there.

1. Download the zipped code from Github (link above). Or fork and then clone it.
2. Run npm install to bring in all the node modules needed.
3. Run the database.sql code in Postico in order to create the books table. It is expecting to be inside  of a database called phi.
4. Alter the books table
5. Run the following query in Postico to add two new columns to our books table.

   ALTER TABLE books
      ADD  COLUMN edition int,
      ADD COLUMN  publisher varchar(120);
Tasks:
1. Update our HTML form to capture those new fields.
2. Update our server-side database queries to use them for insertion.
3. Then update our AJAX GET request to append all of our information to the DOM when it returns successfully so we can see the data from our database.
