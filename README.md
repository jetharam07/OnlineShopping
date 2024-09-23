# OnlineShopping Mern Stack Project
Using React, Express, Node.js, MongoDB (Database).
View from this link:https://onlineshopping-aizl.onrender.com


Mern-stack-project
│
├── frontend
      |___ Client
│            |____ public        # Public (index.html, images)
│            |____ src          # React components, styles etc.
|            |____ package.json   # Dependencies for frontend
|
|____backend
     |____ config          # MongoDB connection
     |____ controllers     # Created all api's for project
     |____ helpers         # Code for password security
     |____ models          # MongoDB models (Schemas)
     |____ routes          # API routes (Express)
     |____ env             # This is a secret file. Everything in it is secret. It should never be made public. (Mongo URL, JWT Secret token, payment related keys)
     |____ package.json         # Dependencies for backend
     |____ server.js       # Main server file (Node + Express)
