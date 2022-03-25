writeCode

Write command to

- List collections from a database.
```js
show collections
```
- create a new collection in your country database which you created recently.
```js
db.createCollections()
```

Write code to:-

- crate a database named `weather`
- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.
- create a simple collection named `humidity`
- db.createCollection( "log", { capped: true, size: 100000 } )
- Delete `humidity` collection and then the entire database(weather).
