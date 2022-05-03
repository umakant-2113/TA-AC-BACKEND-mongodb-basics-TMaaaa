writeCode

Write command to

- List collections from a database.
<!-- show dbs -->
- create a new collection in your country database which you created recently.
<!-- use india -->

Write code to:-

- crate a database named `weather`
<!-- use weather -->
- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.
<!-- dbs.weather.insert({name:"umakant",location:"rath",temerature:30}) -->
- create a simple collection named `humidity`
<!-- use humidity -->
- check whether `temperature` collection is capped or not ?
<!-- dbs.weather.find(id:give the particular id ) -->
- Delete `humidity` collection and then the entire database(weather).
<!-- dv.humidity.drop() -->
<!-- dv.dropDatabase -->
