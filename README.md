# Developer Social Platform

## Overview
Welcome to our Developer Social Platform – a space for developers to connect, share ideas, and engage in meaningful discussions. This web application provides various features including user registration, profile creation, post creation, and interaction through comments.

---

# Quick Start 🚀

### Add a default.json file in config folder with the following

```json
{
  "mongoURI": "mongodb+srv://Satya:zh9cU7U5EWx4Rneo@cluster0.mvali7w.mongodb.net/Cluster0?retryWrites=true&w=majority",
  "jwtSecret": "mysecrettoken",
  "githubClientId": "1c66bd2dd86d0db2d42d",
  "githubSecret": "e7d2807fe6eca6c84849e8e57cf19669a1647630"
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





# Features

# User Registration
New users can register by providing their details on the registration page.

# Login
Registered users can log in securely to access their personalized account.

# Profile Creation and Editing
Users can create and edit their profiles, showcasing their skills and experience.

# Developer Details
View detailed profiles of individual developers on the platform.

# All Developers
Explore a list of all registered developers on the platform.

# Post Creation
Users can share their thoughts, ideas, or ask questions by creating posts.

# Comments
Engage in discussions by commenting on posts and interacting with other developers.

# Technologies Used
Node.js
React.js
MongoDB
HTML/CSS
