# ExpresJS Boilerplate
![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![node](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![mongo](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

A template for your next backend project integrated with ExpressJS, MongoDB and pino-logger, Simply create a `.env` as directed by [`.env.sample`](https://github.com/uzair-ali10/express-boilerplate/blob/master/.env.sample), enter your [MongoDB Atlas Cluster](https://www.mongodb.com/cloud/atlas) URL and get started 🚀

Send initial get request to `http://localhost:8080/api/main/hi`

| File           	| Description                                                           	|
|----------------	|-----------------------------------------------------------------------	|
| `config/db.js` 	| Contains configurations for connecting to MongoDB Atlas Cluster       	|
| `controller/`  	| contains core functions that are to be performed by APIs              	|
| `models/`      	| Contains MongoDB Schema models                                        	|
| `public/`      	| Contains frontend stuff like HTML and CSS                             	|
| `routes/`      	| Contains routes files that defines APIs endpoints                     	|
| `services/`    	| Contains configuration for Services like logging and cronjobs etc etc 	|