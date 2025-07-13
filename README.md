
# DevConnector 🚀

DevConnector is a full-stack social network application built with the MERN stack (MongoDB, Express, React, Node.js). It allows developers to create profiles, connect with others, and share posts.



## Installation

Follow these steps to get the project running locally:

```bash
    # Clone the repository
    git clone https://github.com/GunSinghal/DevConnector.git
    cd DevConnector

    # Install backend dependencies
    npm install

    # Install frontend dependencies
    cd client
    npm install

    # Go back to root
    cd ..

    # Start both client and server
    npm run dev
```
    
## Usage/Examples

```javascript
1. Register a user on the platform.
2. Create your profile with skills, experience, and education.
3. Browse other developers' profiles.
4. Share posts, like, and comment on them.
5. Edit or delete your content anytime.
```


## API Reference

### 🧑‍💻 User Routes

- `POST /api/users` — Register a new user  
- `POST /api/auth` — Authenticate user and return JWT  
- `GET /api/auth` — Get the current logged-in user  

### 👤 Profile Routes

- `GET /api/profile/me` — Get current user's profile  
- `POST /api/profile` — Create or update a user profile  
- `GET /api/profile` — Get all user profiles  
- `GET /api/profile/user/:user_id` — Get profile by user ID  
- `DELETE /api/profile` — Delete profile, user & posts  
- `PUT /api/profile/experience` — Add profile experience  
- `DELETE /api/profile/experience/:exp_id` — Delete experience  
- `PUT /api/profile/education` — Add profile education  
- `DELETE /api/profile/education/:edu_id` — Delete education  

### 📝 Posts Routes

- `POST /api/posts` — Create a new post  
- `GET /api/posts` — Get all posts  
- `GET /api/posts/:id` — Get post by ID  
- `DELETE /api/posts/:id` — Delete a post  
- `PUT /api/posts/like/:id` — Like a post  
- `PUT /api/posts/unlike/:id` — Unlike a post  
- `POST /api/posts/comment/:id` — Add a comment  
- `DELETE /api/posts/comment/:id/:comment_id` — Delete a comment  

## Features

- User registration and authentication (JWT)
- Create and manage profiles
- Add experience and education
- Post creation, likes, and comments
- Responsive UI using React



## Tech Stack

- MongoDB & Mongoose
- Express.js
- React & Redux
- Node.js
- Axios
- React Router
