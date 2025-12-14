# Dale Livingston II – Portfolio Project  
*SDC 255 – Creating Scalable Foundations*

This project is a personal portfolio webpage designed to showcase my skills, projects, and contact information. It fulfills the requirements of the “Creating Scalable Foundations” assignment, emphasizing well-structured HTML, dynamic JavaScript content, custom objects, and persistent storage using `sessionStorage`.

---

## 🚀 Project Overview

This portfolio page serves as an interactive introduction to my technical background. It includes:

- A dynamic welcome modal
- A dark mode toggle (saved using localStorage)
- A dynamically generated skills list
- Custom JavaScript project objects rendered onto the page
- Persistent storage using `JSON.stringify()`, `JSON.parse()`, and `sessionStorage`
- A functional contact form with timed confirmation
- A tooltip-assisted Submit button

All project data and dynamic elements are created using JavaScript to demonstrate DOM manipulation and scalable web foundations.

---

## 🧩 Technologies Used

### **Languages**
- HTML5  
- CSS3  
- JavaScript (ES6)

### **Libraries / APIs**
- Local Storage API  
- Session Storage API  
- DOM API  

No external JavaScript libraries or frameworks were used. The site is 100% hand-coded.

---

## 📁 Project Objects

Three project objects were created in JavaScript.  
Each contains:

- Project Title  
- Brief Summary  
- Image/Icon URL  
- GitHub Repository Link  

These objects are stored in an array, saved to sessionStorage, and rendered dynamically onto the page.

---

## 🔁 Dynamic Content

### **Skills List (Loop Requirement)**
A JavaScript loop generates a list of at least five skills and injects them into the DOM:

- Cisco Catalyst Switches  
- Juniper Switches  
- Meraki Switches  
- Cisco Voice  
- Python  

### **Project Rendering**
Projects stored in sessionStorage are parsed and displayed on the page when it loads.  
Each project includes:

- Project image  
- Title  
- Description  
- Link to GitHub  

---

## 💾 Persistent Storage

This project uses:

- `JSON.stringify()` to store objects as strings  
- `sessionStorage.setItem()` to save data  
- `JSON.parse()` to retrieve and restore objects  

This ensures that project data persists during a browser session and is repopulated dynamically upon reload.

---

## 🎨 Features & Functionality

### ✔ Dark Mode  
User preferences are saved using localStorage.

### ✔ Modal Popup  
A welcome message appears when the page loads.

### ✔ Tooltip Feedback  
Hovering over the Submit button displays a helpful message.

### ✔ Contact Form  
Displays a success confirmation using timed JavaScript logic.

### ✔ Clean, Organized Layout  
All elements are formatted and structured for readability and usability.

---

## 📂 File Structure

