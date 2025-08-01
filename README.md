✨ Features
Add new interns (name, email, department)

View intern list in a table

Delete interns

Responsive and minimal UI

Built using RESTful API architecture

🛠 Tech Stack
Frontend: React, Axios

Backend: Node.js, Express

Database: MongoDB, Mongoose

Tools: npm, VS Code, Postman

📁 Project Structure
bash
Copy
Edit
intern-dashboard/
├── backend/
│   ├── server.js
│   ├── models/Intern.js
│   └── routes/interns.js
└── frontend/
    └── src/
        ├── App.js
        ├── components/
        │   ├── AddIntern.js
        │   └── InternList.js
🚀 Getting Started
⚙️ Backend Setup
bash
Copy
Edit
cd backend
npm install express mongoose cors
node server.js
Runs backend server at: http://localhost:5000

🌐 Frontend Setup
bash
Copy
Edit
cd frontend
npx create-react-app .
npm install axios
npm start
Runs frontend app at: http://localhost:3000

🌐 API Endpoints
Method	Endpoint	Description
GET	/api/interns	Get all interns
POST	/api/interns	Add a new intern
DELETE	/api/interns/:id	Delete an intern

🖼 Example UI
less
Copy
Edit
Intern Dashboard

[ Name ][ Email ][ Department ] [Add Intern]

--------------------------------------------------
| Name     | Email           | Department | [X] |
--------------------------------------------------
📦 Example Intern Data (MongoDB)
json
Copy
Edit
{
  "_id": "64ee2fa945f7e8faba123456",
  "name": "Alice",
  "email": "alice@demo.com",
  "department": "Finance"
}
🧪 Example Use Case
Open the dashboard in your browser

Enter intern info: name, email, department

Click "Add Intern"

Intern appears in the list

Click "Delete" to remove an intern

📌 Requirements
Node.js and npm installed

MongoDB running locally or Atlas URI

Internet connection (for React dependencies)

