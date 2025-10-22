# What Did You Get Done?

A unified platform for cross-tool project progress tracking. `web` contains the frontend, `server` contains the backend.

## Run Instructions

1. Define environment variables

For both `web` and `server`, copy the variables in `.env.example` to your own `.env` file.

2. Install packages and start frontend

```
cd web
npm i
npm run dev
```

3. Create virtual Python environment

```
python3 -m venv .venv
source .venv/bin/activate
```

4. Install packages and start backend

```
cd server
pip install -r requirements.txt
pip install "fastapi[standard]"
fastapi dev main.py
```
