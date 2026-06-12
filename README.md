# Order Track

> Abstract : Problem Statement  
Current manual order management in local shops leads to human error, slow product lookup, and excessive paper use. There is no real-time stock monitoring, making accurate daily/weekly sales reports difficult. This project digitizes records to improve efficiency and reliability.  
Order Track is a web-based Shop Management System that replaces manual registers with a centralized database to automate order tracking, inventory updates, and report generation.

## Deployment Steps
Follow these steps to run the project locally:
1. Clone the repository:
   ```
   git clone <repo-url>
   cd biryani-shop-main
   ```
2. Install backend dependencies:
   ```
   npm install
   ```
3. Create a `.env` file (copy `.env.example`) and set required variables:
   - PORT (default 3000)
   - DATABASE_URL
   - JWT_SECRET
4. Start or configure the database (Postgres/MySQL) and run migrations/seeders:
   ```
   npm run migrate
   npm run seed
   ```
5. Start the development server:
   ```
   npm run dev
   ```
6. Open the app in a browser:
   ```
   http://localhost:3000
   ```
7. Run tests:
   ```
   npm test
   ```


## Platform, Libraries and Frameworks used
1. Node.js — https://nodejs.org  
2. Express.js — https://expressjs.org  
3. TensorFlow.js — https://tensorflowjs.com

