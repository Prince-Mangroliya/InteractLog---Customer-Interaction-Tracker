# 📒 Customer Interaction Logger
**(CRM-Based, Beginner-Friendly)**

---

## 📌 Overview:
Develop a **Customer Interaction Logger** app designed for sales or client relationship professionals. This app will allow users to:  
- ✅ **Log details** of each customer interaction.  
- 🔄 **Track follow-ups** for better client management.  
- 🔍 **Filter logs** based on mood or interaction type.  

This project is ideal for learning **Redux** as it involves managing state across multiple components.

---

## 🚀 Key Features & Requirements:

### 1. ⚙️ State Management:
- **Use Redux** to manage the state of interaction records.  
- Define actions for:  
  - `ADD_INTERACTION`: ➕ Add a new customer interaction.  
  - `UPDATE_INTERACTION`: ✏️ Edit existing interaction details.  
  - `DELETE_INTERACTION`: 🗑️ Remove an interaction entry.  
- Implement corresponding **reducers** to update the state based on these actions.  

---

### 2. 🎨 User Interface:
- **Form for Logging Interactions:**  
  - Fields to include:  
    - 🧑 **Customer Name**  
    - 📞 **Interaction Type** (e.g., Call, Meeting, Email)  
    - 📅 **Date of Interaction**  
    - 📝 **Notes or Summary**  
    - 😊 **Mood Rating** (e.g., Positive, Neutral, Negative)  
- **Display Logged Interactions:**  
  - 📋 List all recorded interactions.  
  - 🔎 Provide filter options to sort interactions by:  
    - Type of Interaction  
    - Mood Rating  

---

### 3. 🖱️ Interactivity:
- Allow users to:  
  - ✏️ **Edit** an interaction entry if details change.  
  - 🗑️ **Delete** an interaction that is no longer relevant.  
- Optionally, integrate **Redux DevTools** to:  
  - 🕵️‍♂️ Monitor state changes.  
  - 🐞 Debug actions and reducers.  

---

## 🎯 Learning Outcomes:
By building this app, you will:  
- 🛠️ **Practice basic Redux concepts**, including:  
  - Actions  
  - Reducers  
  - Store Setup  
- 🔗 Learn to **connect React components to a Redux store** using:  
  - `useSelector` to read state from the store.  
  - `useDispatch` to dispatch actions and update the store.  

---

This project is perfect for beginners wanting to understand **Redux** with React and gain hands-on experience in state management! 🚀
