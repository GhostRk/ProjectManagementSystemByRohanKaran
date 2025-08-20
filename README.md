# ProjectManagementSystemByRohanKaran
project management system 

# 🛠️ Project Management System (WIP)

A full-stack project management system built with:

- **Frontend:** React + TypeScript + Vite + TailwindCSS  
- **Backend:** Django + GraphQL (Graphene)  
- **Database:** PostgreSQL  
This project is still under development 🚧. Expect broken features and unfinished UI.  

---

## 📂 Project Structure


Backend Setup (Django + GraphQL)
cd pm_backend
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Mac/Linux

pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver


Backend runs at:
👉 http://127.0.0.1:8000/graphql/

3. Frontend Setup (React + Vite)
cd pm_frontend
npm install
npm run dev


Frontend runs at:
👉 http://localhost:5173

🔧 Environment Variables

Create a .env file in the frontend root:

VITE_GRAPHQL_URL=http://127.0.0.1:8000/graphql/

🚀 Current Features

✅ React frontend with navigation (Projects, Tasks)

✅ TailwindCSS dark theme styling

✅ Django backend with GraphQL API

❌ Authentication (WIP)

❌ CRUD operations for Projects & Tasks (WIP)

❌ CORS config (buggy, under fix 🐛)
