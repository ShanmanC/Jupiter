# Jupiter
a ticket search and recommendation website

My web site can do following things:
  1. Search for events nearby, giving a geo location, return a list of events. 
  2. Recommend events for the user, giving user information, return a list of recommended events. 
  3. Get user favorite events, giving user information, return a list of favorite events. 
  4. Set/Unset user favorite events, giving user information and events to set/unset, return OK if operation is successfully done. 
  5. Login. 

when use database 
MySQL:
goes to  MySQLDBUtil.java change the port number to 8889, open MAMP
goes to DBConnectionFactory.java change default db = mysql
userid:1111
password:2222

MongoDB:
terminal:
cd ~/Documents/Project/mongodb-osx-x86_64-4.0.4
./bin/mongod --dbpath db/

another terminal:
cd ~/Documents/Project/mongodb-osx-x86_64-4.0.4
 ./bin/mongo
use recommend
if want to see users in the database
db.users.find()

goes to DBConnectionFactory.java change default db = mongodb

