# Fast_API
A beginner-friendly FastAPI project to explore modern API development using Python. Includes examples of path parameters, query handling, and structured responses.

# 🚀 FastAPI Project

A beginner-friendly FastAPI project that demonstrates how to build and run APIs using Python’s modern, high-performance web framework — **FastAPI**.

---

## 🧩 Features

- Dynamic routes with **Path** and **Query** parameters  
- RESTful API design with multiple endpoints  
- JSON response handling  
- Error handling using FastAPI  
- Real-time API testing with **Uvicorn**

---

## 🧠 Concepts Covered

- **FastAPI setup** and app structure  
- **Path parameters** with validation (e.g. `/get-item/{item_id}`)  
- **Query parameters** for flexible searching  
- **Exception handling** for missing data  
- Returning structured **JSON** responses

---

## 🛠️ Tech Stack

- **Language:** Python 3.x  
- **Framework:** FastAPI  
- **Server:** Uvicorn  

---

## ⚙️ Installation and Setup

### 1️⃣ Clone the repository 
```bash
git clone https://github.com/YourUsername/FastAPI.git
cd FastAPI

2️⃣ Create and activate a virtual environment
python -m venv env
env\Scripts\activate  # On Windows
source env/bin/activate  # On macOS/Linux

3️⃣ Install dependencies
pip install fastapi uvicorn

4️⃣ Run the server
uvicorn Working:app --reload
(Replace Working with your main file name if different)


🔍 Example Endpoints
1️⃣ Get item by ID

GET /get-item/{item_id}
Returns the details of a specific item from the inventory.

2️⃣ Get item by name

GET /get-by-name?name=Milk
Fetches an item by its name using query parameters.

💡 Example Response

{
  "name": "Milk",
  "price": 3.99,
  "brand": "Regular"
}

🧑‍💻 Author

Abubakar Awan
💼 Python Developer | Backend Learner | FastAPI Enthusiast
📍 Karachi, Pakistan
🔗 LinkedIn

🌟 Acknowledgment

Special thanks to my mentor @Qasim Hassan for guidance and continuous support throughout my FastAPI learning journey.

