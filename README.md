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
