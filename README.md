# firebase-import-export
## firebase import export tool for database backup

###### install using NPM 
** npm install firestore-export-import **

###### Get your Google Cloud Account Creditals from Firebase
> you can ** generate new private key ** from project settings from firebase console and paste it to serviceAccountKey.json.

###### Exporting data from firebase/firestore

```
node export.js <collection_name>
```
> note: after exporting, you need to copy the json file from <firestore-export.json> into another json file as your back-up file.

###### Importing data from back-ip to firebase/firestore

```
node import.js import-to-firestore.json
```

> note: import-to-firestore.json must contain the specific json file from your collection, for example: users collection etc..


i hope it helps.. happy coding <3 