for easy understanding of this project, follow this step below.
1. create a new folder inside any path of your pc either Mac or window.

2. open your terminal. for Mac pc use CMD + D. 

3. for windows user, create a new folder with <mkdir new_folder> in your terminal.

4. open your project folder into your favorite text_editor, for me i prefer vscode with code .

5. create a new json file with NPM init -y to initialise a new json file.

6. install the all depencies and devDepencies. inside the package.json file

7. create a .env file inside the root of your folder.

8. create and account with mongoDB or you can sign in if you have an existing account.

9. connect your database, copy the cluster url and paste inside your .env file DATABASE_URL=mongodb+srv://<name>:<password>@cluster0.mrkokwz.mongodb.net/?retryWrites=true&w=majority

10. create a new file server.js. 

require("dotenv").config();
const multer = require("multer");
const mongoose = require("mongoose");
const bcrypt = require("bcrypt");
const File = require("./models/File");

const port = process.env.PORT || 3001;

const express = require("express");
const app = express();


11. run your app with port 3001 inside your teminal


