# Node.js CRUD API

This is a simple Node.js and Express.js CRUD API that allows you to manage users with the following operations:

- Create a new user
- Read all users or a single user by ID
- Update user details
- Delete a user

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

## 🧪 API Endpoints

| Method | Route         | Description         |
|--------|---------------|---------------------|
| GET    | `/`           | Get all users       |
| GET    | `/:id`        | Get a user by ID    |
| POST   | `/`           | Create a new user   |
| PATCH  | `/:id`        | Update a user       |
| DELETE | `/:id`        | Delete a user       |

## 🚀 How to Run

1. Clone the repo:
   ```bash
   
  
