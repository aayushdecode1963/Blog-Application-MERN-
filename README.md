# Blog App using MERN Stack

## Functionalities

- **Authentication:** Secure user authentication system to protect your blogs.
- **Create Blog:** Easily create and publish your blogs with a user-friendly interface.
- **Delete Blog:** Remove unwanted blogs with a simple delete option.
- **Update Blog:** Edit and update your blogs as your content evolves.
- **View Other User Blogs:** Explore and read blogs published by other users.

## Screenshots
![Screenshot 1](https://user-images.githubusercontent.com/67452985/172217325-4378400e-60a0-4364-aadb-89e900886a1c.png)

![Screenshot 2](https://user-images.githubusercontent.com/67452985/172217368-76264e6e-8373-484d-9cd0-3af5920754b1.png)

![Screenshot 3](https://user-images.githubusercontent.com/67452985/172217649-238abde0-1b29-40fe-a46e-1b5bb03678c8.png)

## Getting Started

Steps to Run the Project:

1. Clone the Repository:
   - Run: git clone https://github.com/your-username/Blog-App-using-MERN-stack.git
   - Navigate to the project directory.

2. Set Up Backend:
   - Go to the 'server' folder: cd server
   - Install dependencies: npm install
   - Create a .env file in the 'server' folder and add:
     - MONGODB_URI=your_mongodb_connection_string
     - JWT_SECRET=your_jwt_secret_key

3. Set Up Frontend:
   - Go to the 'client' folder: cd ../client
   - Install dependencies: npm install

4. Set Up MongoDB:
   - Use MongoDB Atlas (recommended) or set up MongoDB locally.
   - Create a MongoDB cluster, get the connection string, and add it to the `.env` file.

5. Run the Backend:
   - Inside the 'server' folder, run: npm start
   - This will start the backend on http://localhost:5000.

6. Run the Frontend:
   - Inside the 'client' folder, run: npm start
   - This will start the frontend on http://localhost:3000.

7. Open the App:
   - Go to http://localhost:3000 in your browser to access the app.

How to Use:
- Register or login to the app.
- Create, edit, or delete blog posts if you have admin privileges.
- View all blog posts on the homepage.

Troubleshooting:
- Ensure MongoDB URI is correct in the .env file.
- Make sure the backend and frontend are running without errors.

Enjoy blogging!

