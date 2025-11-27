# codsost-1
This is a simple content-based Movie Recommendation System built using HTML, CSS, and JavaScript. It recommends movies based on user input such as genre or keywords. The system matches the user’s preferences with a small movie dataset and displays relevant suggestions instantly on the webpage. It works completely on the client side 
# 🎯 Simple Recommendation System (HTML + CSS + JavaScript)

This is a beginner-friendly **Recommendation System** built using **pure HTML, CSS, and JavaScript**.  
It suggests items to users based on their **preferences** using a simple **Content-Based Filtering** technique.

This project is suitable for:
- Mini Projects  
- College Submissions  
- Learning Recommendation Systems  
- GitHub Portfolio Projects  

---

## 📌 Features
- Users can select a profile (User 1, User 2, User 3)
- System recommends items based on predefined categories
- Fully client-side (no backend required)
- Clean UI using simple CSS
- Ready to deploy on GitHub Pages

---

## 📁 Project Structure
recommendation-system/
│── index.html → Main Interface
│── style.css → Styling
│── script.js → Recommendation Logic
│── README.md → Documentation

---

## 🚀 How It Works

### 1️⃣ User Preferences  
Each user has favorite categories such as Action, Romance, Comedy, etc.

```javascript
const userPreferences = {
    user1: ["Action", "Adventure", "Sci-Fi"],
    user2: ["Romance", "Drama"],
    user3: ["Comedy", "Fantasy"]
};
 2️⃣ Item Database

const items = [
    { name: "Avengers", category: "Action" },
    { name: "Interstellar", category: "Sci-Fi" },
    { name: "John Wick", category: "Action" },
    { name: "The Notebook", category: "Romance" },
    { name: "La La Land", category: "Drama" },
    { name: "Harry Potter", category: "Fantasy" },
    { name: "Deadpool", category: "Comedy" }
];
