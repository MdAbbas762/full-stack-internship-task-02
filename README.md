# full-stack-internship-task-02  

This project is a basic full-stack web application created for **Task 2** of the Full Stack Development internship, at **CoreTech Innovations**.  
It includes a frontend form, a Node.js + Express backend, and a MongoDB database for storing form submissions.  

---  

## ✨ Features  

### **Frontend (HTML + CSS + JavaScript)**  
- Header with navigation bar  
- Registration form (Name, Email, Password, Message)  
- CSS styling for layout and spacing  
- JavaScript form validation  

### **Backend (Node.js + Express)**  
- `GET /` route serves the HTML file  
- `POST /submit` route handles form submission  
- `express.urlencoded()` parses form data using   
- `express.static()` serves static files automatically  


### **Database (MongoDB + Mongoose)**  
- `mongoose` library facilitates to build connection between Node.js app and MongoDB server  
- Stores user details in a MongoDB collection  
- Fields: **name, email, password, message**  
- Simple schema with validation rules  
- A model to interact with database and insert data  

---  

## 📃 Notes  

- This project is completed according to the assignment requirements.  
- The code is simple, clean, and easy to understand.  
- All frontend files are placed inside the `public` folder and served as static assets.  
