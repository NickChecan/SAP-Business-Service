# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File / Folder | Purpose
---------|----------
`app/` | content for UI frontends go here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps...

- Open a new terminal and run  `cds watch`
- ( in VSCode simply choose _**Terminal** > Run Task > cds watch_ )
- Start adding content, e.g. a [db/schema.cds](db/schema.cds), ...


## Learn more...

Learn more at https://cap.cloud.sap/docs/get-started/

Node version: 8.11.3 (Use n or nvm to manage node versions)
- cds init my-bookshop (To create the project)
- npm i --save sqlite3 (Use on the project folder to install sqlite3 for local/persistent tests)
- npm i (Use on the project folder to install the dependencies)
- cds watch (To run the project locally)
- cds deploy --to sqlite:db/my-bookshop.db (Deploy to sqlite for a persistent database)
- sqlite3 db/my-bookshop.db -cmd .dump (Show executed commands)
- sqlite3 db/my-bookshop.db (Connect to the local environment database)