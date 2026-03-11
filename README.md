# lab-deepreseach

`lab-deepreseach` is a dual-stack deep research project adapted from the chapter 14 deep research example and repackaged as an independent portfolio repository.

## Stack

- Backend: FastAPI, Python, uv, Hello-Agents runtime
- Frontend: Vue 3, Vite, TypeScript

## Structure

- `backend`: API service and deep research agent logic
- `frontend`: web client for query submission and report display

## Quick Start

### Backend

```bash
cd backend
copy .env.example .env
uv sync
cd src
uv run python main.py
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## Notes

- This repository is being refactored into the `lab-deepreseach` project and no longer uses the upstream `Hello-Agents` repository layout as its public-facing structure.
- I will continue replacing inherited naming and project-specific behavior in subsequent commits.
