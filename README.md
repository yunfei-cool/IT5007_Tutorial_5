# IT5007_Tutorial_5
MongoDB Exercise for IT5007, NUS

# Function
This project implements the ability to add, delete, and display the waitList of Hotel California.

In order to make the function 'show' more meaningful, every time you press add or delete button, you need to press the show button to see what you do.

# How to run the project in your environment?

npm install

mongo issuetracker scripts/init.mongo.js

npm run compile

npm start

After using these commands, the webpage will show on the port 3000.

# The trymongo.js
just a try to add, delete, update, read the data in the database.
in order to see what I do, you can use the commands below.

mongo issuetracker --eval "db.waitlist.remove({})"

node scripts/trymongo.js