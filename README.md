# 🎬 IMDb Movie Search

A simple Django web application that allows users to search for movies using the **OMDb (Open Movie Database)** API. The app displays detailed movie information such as title, year, genre, director, actors, plot, and IMDb rating, along with the movie poster.

## 🌐 Live Demo
*(Add your deployed link here if you host it later, e.g., on Render or PythonAnywhere)*

## 🧰 Features
- 🔍 Search movies by title  
- 🖼️ View poster, genre, director, actors, and plot  
- ⭐ Shows IMDb ratings  
- ❌ Displays a “Movie not found” message for invalid titles  
- 🎨 Clean, Google-like centered interface  

## 🧱 Tech Stack
- **Frontend:** HTML, CSS  
- **Backend:** Django  
- **API:** [OMDb API](https://www.omdbapi.com/)  

## ⚙️ Installation Guide
### 1️⃣ Clone this repository
git clone https://github.com/yourusername/movie-search.git
cd movie-search
## 2️⃣ Create and activate a virtual environment
bash
Copy code
python -m venv venv
venv\Scripts\activate     # for Windows
source venv/bin/activate  # for macOS/Linux


## 3️⃣ Install dependencies
Copy code
pip install -r requirements.txt


## 4️⃣ Run the Django development server
bash
Copy code
python manage.py runserver
Then open your browser at:
👉 http://127.0.0.1:8000/

## 🔑 Setup OMDb API Key (Optional)
If your project fetches data from the OMDb API using a key, create a .env file in your project root:
ini
Copy code
OMDB_API_KEY=your_api_key_here
Then load it in your Django view using os.environ.get("OMDB_API_KEY").

## 📂 Project Structure

movie-search/
│
├── imbd/                 # Main app
│   ├── templates/        # HTML templates
│   ├── views.py          # Main view logic
│   ├── urls.py
│   └── ...
│
├── manage.py
├── db.sqlite3
└── README.md


## 🧑‍💻 Author
Asif Ali Z
📫 [azifalizakir@gmail.com]
⭐ If you like this project, give it a star on GitHub!

## 🪪 License
This project is open-source and available under the MIT License.


## ✅ Just copy-paste this into a file named **`README.md`** inside your project folder.  







