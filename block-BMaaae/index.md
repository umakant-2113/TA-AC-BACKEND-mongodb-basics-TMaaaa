writeCode

Write code to:-

- create a database named `sports`.
<!-- use sports -->
- list all databases present in local mongod server.
<!-- show dbs -->
- create 3 collections named `cricket`, `football`, `TT` in sports databse.
<!-- db.createCollection(`cricket`, `football`, `TT`) -->
- add multiple players in those collections which should have fields like `name`, `age`
 and `email` and `bid_price`.
 <!-- db.use -->
 <!-- db.cricket.insert({name:rahul,age:23,email:lodhiumakant800@gmail.come,bid_priice:23000}) -->
 <!-- db.football.insert({name:rohit sharama,age:30,email:rahitsharama@gmail.com,bid_price:30000}) -->
 <!-- bd.TT.insert({name:kapil dev,age:40,email:kapilDev@gmail.com,bid_price:40000}) -->
- list all collections in sports database.
<!-- show collections -->
- rename `TT` collection to `tennis`.
<!-- db.TT.rename("tennis) -->
- create a capped collection called `khokho` which should have max 3 documents.
<!-- db.TT.createCollection("khokho") -->
  Try inserting more than 3 and see what happens?
  <!-- db.khokho.insert({name:"umakant"},{age:34},{email:lodhiumakant800@gmail.com}) -->
- check whether a collection is capped or not?
<!-- show dbs -->
- drop all documents from `football` collection.
<!-- db.football.drop() -->
- delete cricket collection completely.
<!-- db.cricket.drop() -->
- delete sports database.
<!-- db.dropDatabase() -->
- check which database you are connected to ?
<!-- bd -->
- connect to test database
<!-- use test -->
