## The node.js Basic Web App


## Common setup

Clone the repo and install the dependencies.

```bash
git clone https://github.com/jugalkishoredots/nodejs.git
cd nodejs

```

```bash
npm install
```

## Steps for read-only access

To start the express server, run the following

```bash
npm run start:dev
```

Open [http://localhost:3000](http://localhost:3000) and take a look around.


Open [http://localhost:3000/admin](http://localhost:3000/admin) for admin panel.

Use this details: 


## Steps for Database (recommended)
```
Step 1: 

open http://localhost/phpmyadmin/

Step 2: 

Login to localhost phpmyadmin 

Step 3: 

Create a new database name 'nodejs'

Step 4: 

run command # npx sequelize-cli db:migrate

Step 5: 

run command # npx sequelize-cli db:seed:all
