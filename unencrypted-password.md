# Unencrypted password

- The current value password in our database is set to a "text" data type rather than a hashed string.

solution: add a hashing script and change the datatype to string.