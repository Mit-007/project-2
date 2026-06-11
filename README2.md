# Multi-Task Project

This repository contains four independent tasks/projects.

## Project Structure

<img width="375" height="358" alt="Screenshot 2026-06-11 214024" src="https://github.com/user-attachments/assets/52c7febc-1b15-4fcc-b5b4-1efd4423964d" />

---

## Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

### 2. Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory (or in the task directory if required) and add the following variables:

```env
GOOGLE_API_KEY="Your_Api_Key"
PINECONE_API_KEY="Your_Api_Key"
```

#### How to Get a Google API Key

1. Visit the Google AI Studio:
   https://aistudio.google.com/
2. Sign in with your Google account.
3. Navigate to **Get API Key**.
4. Create a new API key.
5. Copy the generated key and replace `Your_Api_Key` in the `.env` file.

#### How to Get a Pinecone API Key

1. Visit Pinecone:
   https://www.pinecone.io/
2. Create an account or sign in.
3. Open the Pinecone Console.
4. Create a project if you do not already have one.
5. Navigate to **API Keys**.
6. Copy your API key and replace `Your_Api_Key` in the `.env` file.

---

# Running Individual Tasks

> **Important:** Before running any specific task, please read the `README.md` file inside that task's folder. Each task contains detailed information about its purpose, project structure, functionality, and execution instructions. This will help you better understand the sub-project and how to run it correctly.

## Task-1

Navigate to the task folder:

```bash
cd Task-1
```

Run the application:

```bash
python -m app.main
```

---

## Task-2

Navigate to the task folder:

```bash
cd Task-2
```

Run the application:

```bash
python -m app.main
```

---

## Task-3

Navigate to the task folder:

```bash
cd Task-3
```

Run the application:

```bash
python -m app.main
```

---

## Task-4

Task-4 is a REST API application built with FastAPI.

Navigate to the task folder:

```bash
cd Task-4
```

Start the API server:

```bash
uvicorn app.main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

ReDoc:

```text
http://127.0.0.1:8000/redoc
```

---

## Requirements

All project dependencies are listed in:

```text
requirements.txt
```

Install them before running any task.

---

## Notes

* Ensure Python 3.10+ is installed.
* Activate the virtual environment before running any task.
* Configure the required API keys in the `.env` file before running the applications.
* Read the task-specific `README.md` before running a particular task.
* Each task is independent and can be executed separately.
* Task-4 exposes REST APIs through FastAPI and provides interactive API documentation using Swagger UI.
