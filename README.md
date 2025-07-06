# Node.js CRUD API with Express & MongoDB

This project is a simple Node.js + Express.js CRUD API connected to MongoDB using Mongoose. It manages user records with fields like `first_name`, `last_name`, `email`, and `gender`.

## 📦 Features

- Create a new user
- Get all users
- Get a user by ID
- Update a user by ID
- Delete a user by ID
## 📁 Project Structure

project/
│
├── controllers/
├── middleware/
├── models/
│ └── user.js
├── routes/
│ └── user.js
├── connection.js
├── index.js
├── package.json
└── log.txt

## ⚙️ Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose


## 🌐 API Endpoints

| Method | Endpoint     | Description        |
|--------|--------------|--------------------|
| GET    | `/`          | Fetch all users    |
| GET    | `/:id`       | Fetch user by ID   |
| POST   | `/`          | Create new user    |
| PATCH  | `/:id`       | Update user by ID  |
| DELETE | `/:id`       | Delete user by ID  |

> All endpoints are defined in `routes/user.js`

## 🧾 User Schema (`models/user.js`)

```js
{
  first_name: String, // Required
  last_name: String,  // Required
  email: String,      // Required, Unique
  gender: String      // Required
}


## 🚀 How to Run

1. Clone the repo:
   ```bash
https://github.com/Dasaridileep/CRUDOPERATIONS.git
   npm install
node index.js
Test with Thunder Client/Postman:

Use the base route: http://localhost:3000/ (or your configured port)
  
