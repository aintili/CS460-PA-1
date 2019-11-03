This website requires Node.js and React to run.

Once you have installed Node and React, unzip the file Intili_Rosen_Website.zip

Because the website and database are entirely local you will need to specify the location of the database (the database file is not provided as
we were not instructed to upload it).

To do so, navigate to the directory Web2/reactnodesql, open the file server.js. There is a line of code which looks like the following:

let db = new sqlite3.Database('/home/aintili/.dbeaver4/.metadata/sample-database-sqlite-1/Chinook.db' ...

Change /home/aintili/.dbeaver4/.metadata/sample-database-sqlite-1/Chinook.db to the directory where the database is stored on you computer

To run the website, navigate to the directory Web2/reactnodesql and type (in terminal) the command npm run dev

Any additional node packages, such as sqlite3 and nodemon, should install automatically after referencing
the package.json files in both Web2/reactnodesql and Web2/reactnodesql/client. If this is not the case, try typing the commands:

npm install,
npm update

in both Web2/reactnodesql and Web2/reactnodesql/client.

If for any reason this fails to load please contact us at:
aintili@bu.edu - Anthony Intili
sjrrules@bu.edu - Sam Rosen

