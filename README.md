Ans1 - The SQL Queries are written in the SQL language but in the secure version SQL Alchemy Library of python is used which makes the code shorter.
Ans2 - In the non secure code, the user id is fetched directly but in the secure version, the user id fetched using session. Session remembers the computer and who logged in from the computer.
Ans3 - In the non secure code, user id is fetched using requets.args_id.get(user) but in thesecure code it is fetched using session.get(user_id). Session remembers the computer and who logged in from the computer.
Ans4 - In the non secure code, no condition is written to upload the image files but in the secure code it is written.
