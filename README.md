# CRUDAPP
This is the simple project to implement CRUD application using NodeJS, ExpressJS and MongoDB

follow the step to run in your local repository:
1. npm init (in folder CRUDAPP)
    fill
    package-name: crud_app
    version : (default)
    description : crudapplication with expressjs and mongodb
    entry point: server.js
    test command: (default)
    git repository : (default)
    keyword: crud, mongodb
    author: (fill as you wish)
    license: (default)
    
 2. npm i express morgan nodemon ejs body-parser dotenv mongoose axios
 3. Create a new cluster in your mongodb dashboard.
 4. in config.env file, copy the link to connect the project to mongodb and created it to PORT variables
    like this: 
    PORT = 3000
    MONGO_URI = mongodb+srv://admin:admin123...........
