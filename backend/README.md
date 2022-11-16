# Backend

This implementation is for NodeJS based on [Express](https://expressjs.com/) and [MongoDB](https://www.mongodb.com/) and uses [mongoose](https://mongoosejs.com/) as the ODM.

## Project setup
```
npm install
```

### Before startup 
Setup a .env file with the following variables, e.g.: mongo_url and organization.
The mongo_URL is from MongoDB cloud. The username is student and the password is professor. With the cloud database, the information is not saved to a local database. As a result, the information can be retrieved from anywhere.

```
MONGO_URL = mongodb+srv://student:professor@cluster0.chobn7e.mongodb.net/eventorganizer

organization = Test A
```

### Compiles and hot-reloads for development
```
npm start
```
