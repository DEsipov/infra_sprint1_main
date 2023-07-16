# **<span style="color:orange">Kittygram</span>**

Kittygram — social network for sharing photos of your beloved pets. It is a fully working project that consists of a Django backend and a React frontend applications.

## Requillrements

- Python 3.10+
- Node.js 18.16.0

# How to install

### Clone the repository and open project directory using command-line

```bash
git clone https://github.com/igoralebar/infra_sprint1.git
cd infra_sprint1
```

## Frontend (React)

### 1. Navigate to `frontend`

```bash
cd frontend
```

### 2. Install dependency

```bash
npm install
```

### 3. Start the server

```bash
npm start
```

### 4. To build for production (Optional)

```bash
npm run build
```

## Backend (Django)

### 1. Navigate to `backend`

```bash
cd backend
```

### 2. Create and activate a virtual environment

- GNU/Linux or MacOS:

  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

- Windows:
  ```bash
  python -m venv venv
  source venv/Scripts/activate
  ```

#### 3. Install all necessary dependencies from `requirements.txt`

    python -m pip install --upgrade pip
    pip install -r requirements.txt

#### 4. Apply migrations

    python manage.py migrate

#### 5. Run the project

    python manage.py runserver

## All done!

With both frontend and backend running you can navigate to `127.0.0.0:3000` to use the project.
