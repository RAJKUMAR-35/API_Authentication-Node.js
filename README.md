# API Authentication using NodeJs

This is an Authentication API using JWT.
## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/API-Authentication-NodeJs.git
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=mongodb://localhost:27017
DB_NAME=YOUR_DB_NAME
ACCESS_TOKEN_SECRET=GENERATE_FROM_GENERATE_KEYS_FILE_IN_HELPER
REFRESH_TOKEN_SECRET=GENERATE_FROM_GENERATE_KEYS_FILE_IN_HELPER
```

Step 4: To generate 256-bit keys for JWT

```bash
node ./helpers/generate_keys.js
```

Step 5: Install Redis (Linux Ubuntu)

```bash
sudo apt-get install redis-server
```

Step 6: Run Redis Server (Linux Ubuntu)

```bash
redis-server
```

Step 7: Install MongoDB (Linux Ubuntu)

See <https://docs.mongodb.com/manual/installation/> for more infos

Step 8: Run Mongo daemon

```bash
sudo service mongod start
```

Step 9: Start the API by

```bash
npm start
```
