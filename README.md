<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Roomble&animation=fadeIn&type=soft&color=gradient&height=150"/>
</p>


Roomble is a real-time chat application built with Flask and Flask-SocketIO that allows users to create or join chat rooms and interact with others instantly. This app allows users to create or join rooms, send messages, and interact in a live chat environment.

## Features

- **Real-time messaging** using Flask-SocketIO
- **Room creation and joining** with unique room codes
- **User sessions** to persist room and user data

## Requirements

- Python 3.7 or higher
- Flask
- Flask-SocketIO
- python-dotenv (for loading environment variables)

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/EmileGreyling/Roomble.git
   cd Roomble
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Set up environment variables:**

   Create a `.env` file in the root directory of the project and add the following line:

   ```env
   SECRET_KEY=your_secret_key_here
   ```

   Make sure to replace `your_secret_key_here` with a securely generated key (you can use [this tool](https://randomkeygen.com/) to generate a strong key).

6. **Run the app:**

   ```bash
   python app.py
   ```

7. Open your browser and go to [http://localhost:5000](http://localhost:5000) to start using the app!

## Acknowledgments

This project was inspired by a Flask chat app tutorial by Tech With Tim, but I have made several custom modifications and improvements.