
# HOTPLATE
A full-stack food delivery system with separate **backend**, **frontend**, and **admin** panels.


## 📂 Project Structure
Food-Delivery-App/

├── backend/ ← API server (Node.js + Express + MongoDB)   
├── frontend/ ← User-facing app (React)  
└── admin/ ← Admin dashboard (React)








## 🧩 Features

- User registration/login, authentication
- Browse food items,Search food items ,add to cart
- Place orders and view order history
- Admin panel to manage items, orders, users
- Separation of concerns: API, user front end, admin front end



## 🛠 Tech Stack

- **Backend**: Node.js, Express.js, MongoDB
- **Frontend / Admin**: React.js, CSS, Axios
- RESTful API endpoints



## 🚀 Getting Started
## 1. Clone the repository


git clone https://github.com/vaib65/Food-Delivery-App.git

cd Food-Delivery-App



    
## 2. Install dependencies
```bash
For Backend
  cd Backend
  npm install
```
```bash
For Frontend
 cd ../frontend
 npm install

```
```bash
For Admin
  cd ../admin
  npm install
```

## 3.Setup environment variables

To run this project, you will need to add the following environment variables to your .env file

`MONGO_URI=your mongodb string connection`

`JWT_SECRET=your jwt secret`

`PORT=`

`STRIPE_SECRET_KEY=your stripe secret key `


## 4. Running the app
```bash
For Backend
  cd Backend
  npm run server
```
```bash
For Frontend
 cd ../frontend
 npm run dev

```
```bash
For Admin
  cd ../admin
  npm run dev
```
