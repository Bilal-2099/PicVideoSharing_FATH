# PicVideoSharing_FastAPI

A simple demo social app built with **FastAPI** that allows users to upload and share photos and videos.

## 🚀 Features
- User registration and authentication
- Upload photos and videos
- File validation
- Static file serving
- RESTful API endpoints
- Swagger UI documentation
- Automatic request validation with Pydantic

## 📚 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /uploads/ | Upload a photo  or video |
| DELETE | /posts/post_id | Delete Post |
| GET | /feeds | List uploaded media |

## Built With

- FastAPI
- Pydantic
- Uvicorn
- Python
- SQLAlchemy
- JWT

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Bilal-2099/PicVideoSharing_FastAPI.git
cd PicVideoSharing_FATH
pip install -r requirements.txt
```

## ▶️ Usage
Run the FastAPI server:

```bash
uvicorn main:app --reload
```

Open your browser at `http://127.0.0.1:8000` to access the app.

## 🛠 Tech Stack
- [FastAPI](https://fastapi.tiangolo.com/) — modern Python web framework
- Python 3.x

## Future Improvements

- PostgreSQL integration
- Likes and comments
- Pagination
- Docker support
- Cloud storage (AWS S3)

## 📂 Project Structure
```
PicVideoSharing_FATH/
│── main.py          # FastAPI entry point
│── requirements.txt # Dependencies
```

## 🤝 Contributing
This is a demo project, but feel free to fork and experiment!
