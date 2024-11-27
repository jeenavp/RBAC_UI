# RBAC_UI

This is a Role Based Access Control application using Nodejs, Express, Passport Js, etc.
This application is my learning from a video tutorial which serves as a starting point for related projects which needs authentication and authorization.

For authentication, only email and password option.

The application is based on the **MVC pattern** : Model View Controller.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.

The application is _almost_ **production ready**.

---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/jeenavp/RBAC_UI.git
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```

Step 4: Install MongoDB 

See <https://www.mongodb.com/docs/manual/installation/> for more info

Step 5: Run Mongo daemon

```bash
sudo service mongod start
```

Step 6: Start the app by

```bash
npm start
```

## Author

- **Jeena V P**

- ## License

This project is licensed under the MIT License.

