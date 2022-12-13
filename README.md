# DevEarth
* DevEarth is a social media platform for developers where developers can connect with other developers in their respective fields.
* It is a small social network app that includes authentication, profiles and forum posts.
* Dev Connector is a Social media for developers all around the world to share their developer stories, interesting insights and grow together.

---
## I have built this as a learning project. These were my learnings :

* Building an extensive backend API with Node.js & Express
* Protecting routes/endpoints with JWT (JSON Web Tokens)
* Extensive API testing with Postman
* Integrating React with our backend in an elegant way, creating a great workflow
* Building our frontend to work with the API
* Using Redux for app state management
* Creating reducers and actions for our resources
* Creating many container components that integrate with Redux
* Testing with the Redux Chrome extension
* Creating a build script, securing our keys and deploy to Heroku using Git

---

## Tech Stack

- MongoDB
- Express.js
- React
- Node.js
- React Redux
- Mongoose


* DevConnector is a full stack application built on the MERN stack (MongoDB, Express, React and Node) and utilises a range of open source libraries to assist with accelerating development time and improving authentication security. MongoDB was chosen as the Database Management System (DBMS) for several reasons, including that it affords dynamic and flexible document schemas that can contain a wide range of data attached to both patients and doctors respectively. Furthermore, MongoDB stores document data in Binary JSON (BSON), which integrates seamlessly with the core JavaScript-driven technologies of DevConnector’s tech stack.

* React is utilised on the front-end of DevConnector, and is primarily responsible for handling the view layer of the application, including the user interface (UI), text, images, and making networking requests to API endpoints. The framework supports building reusable components that dramatically improve code quality, efficiency, and the scalability of the codebase. Express and Node are the server-side technologies that handle the backend business logic of DevConnector, including routing, middleware integration, and network requests to RESTful API endpoints. React-Redux is used for global state control and management of themes across the entire application.

* A JSON Web Token strategy for authentication of users will be employed. It allows RESTful endpoints to be authenticated without needing sessions. A local username and password authentication strategy is also being considered, to allow users to authenticate using a username and password stored in the Node.js application, to provide a familiar login flow for users of the application. 

* Mongoose will be used with our MongoDB implementation, it is an Object Data Modelling (ODM) library for use with MongoDB and Node.js. It assists in managing the relationships between data, provides schema validation and is used to translate between objects in Node.js code and the representation of those objects in MongoDB.


* DevConnector is a single page application (SPA) that utilises the dashboard component as the main wrapper element for rendering various view layers.

* Unauthenticated users can ONLY use the dashboard to view the developers profile. All other application features sit behind protected routes, and attempting to access them will push the browser navigation to the authentication component view.

---


## Target Audience

* Mainly designed for the buddies who are very eager to learn programming and they miss the oppurtunity to connect with senior or skilled devleopers. This platform will be a sugar syrup for them to build a sweet applications.

---

# Quick Start 🚀

### Add a default.json file in config folder with the following

```json
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```

### Test production before deploy

After running a build in the client 👆, cd into the root of the project.  
And run...

Linux/Unix

```bash
NODE_ENV=production node server.js
```

Windows Cmd Prompt or Powershell

```bash
$env:NODE_ENV="production"
node server.js
```

Check in browser on [http://localhost:5000/](http://localhost:5000/)

---

## App Info

### Author

Tejender Upadhyay

### Version

1.0.0

### License

This project is licensed under the MIT License
