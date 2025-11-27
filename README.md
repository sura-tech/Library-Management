📚 Library Inventory Management System

A full-stack web application built using Node.js, Express, EJS, and MongoDB for managing books, tracking availability, borrowing/returning books, and viewing popular books.
Includes a modern UI with Dark Mode.

🚀 Features

✔ Add new books
✔ View all books
✔ Search by author or tag
✔ Borrow & return books
✔ Track availability
✔ Most-borrowed books (MongoDB aggregation)
✔ Clean UI with Dark Mode toggle
✔ Bootstrap responsive layout

🛠️ Tech Stack
Layer	Technology
Frontend	EJS, Bootstrap 5, CSS
Backend	Node.js, Express.js
Database	MongoDB
Tools	Nodemon, MongoDB Shell
📦 Installation & Setup

Follow these steps to download, install, and run this project on your machine.

1️⃣ Clone the Repository
git clone https://github.com/YOUR_GITHUB_USERNAME/library-management.git


Move into the project folder:

cd library-management

2️⃣ Install Dependencies
npm install


This will install:

express

mongodb

ejs

nodemon

bootstrap (CDN)

3️⃣ Install & Run MongoDB

Make sure MongoDB is installed on your system.

If MongoDB is not installed:

Download it here:
https://www.mongodb.com/try/download/community

Start MongoDB service:

mongod


Or ensure MongoDB is running in background.

4️⃣ Start the Application

For development:

npm run dev


For normal run:

npm start


Server will start at:

http://localhost:3000

5️⃣ Seed Books (Optional)

If you want to add books to the database using Mongo Shell:

mongosh
use libraryDB
db.books.insertMany([...])

📁 Project Structure
library-management/
│── index.js
│── package.json
│── public/
│     ├── style.css
│     └── theme.js
│── views/
      ├── partials/
      │     ├── header.ejs
      │     ├── footer.ejs
      ├── index.ejs
      ├── books.ejs
      ├── addBook.ejs
      ├── search.ejs
      ├── mostBorrowed.ejs

🧪 Testing

You can test API routes using tools like:

Postman

Thunder Client (VS Code)

🧑‍💻 Contributing

Feel free to fork this repo and submit pull requests.
All contributions and improvements are welcome!

⭐ Support

If you find this project helpful:

Star ⭐ the repository on GitHub

Share it with others

Follow for more projects

📜 License

This project is open-source and available under the MIT License.
