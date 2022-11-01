➜ startUpTwo npm init -y

➜ startUpTwo npm install express mongoose cors morgan

➜ startUpTwo npm install nodemon --save-dev

➜ startUpTwo mkdir db models controllers routes
➜ startUpTwo touch server.js
➜ startUpTwo touch db/index.js
➜ startUpTwo touch models/index.js
➜ startUpTwo touch controllers/index.js
➜ startUpTwo touch routes/index.js

➜ startUpTwo git init -b main
Initialized empty Git repository in /Users/joshualevine/ga_seir/projects/startUpTwo/.git/

➜ startUpTwo git:(main) ✗ touch README.md

--> then go to github and set up a new repo
git@github.com:jadlevine/start_up_2.git

➜ startUpTwo git:(main) ✗ npx create-react-app client

///prompted me to add node-modules to /.gitignore

then
----> go to client/.gitignore and add package-lock.json to bottom (line 25)

then
cmd+C, cmd-V for all of .gitignore

➜ startUpTwo git:(main) ✗ git add .
➜ startUpTwo git:(main) ✗ git commit -m "Initial setup complete"

➜ startUpTwo git:(main) cd client
➜ client git:(main) ✗ npm install axios react-router-dom
➜ client git:(main) ✗ npm install

Add:
"start": "node server.js",
"dev": "nodemon server.js"
to
"scripts": {
"test": "echo \"Error: no test specified\" && exit 1",
"start": "node server.js",
"dev": "nodemon server.js"
},
in root/backend package.json

FINALLY, connect to remote and push
➜ client git:(main) ✗ git remote add origin git@github.com:jadlevine/start_up_2.git
➜ client git:(main) ✗ git push origin main
