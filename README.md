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
