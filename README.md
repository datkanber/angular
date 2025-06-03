# Full Stack Starter

This repository provides a simple Node.js/Express backend and a Bootstrap-based frontend. It is intended as a starting point for projects that require a responsive design with reusable navigation and footer components.

## Backend

The backend is located in the `backend` folder and uses Express with EJS templates.

### Install dependencies
```bash
cd backend
npm install
```

### Run the server
```bash
npm start
```
The server listens on port **3000** by default and serves the frontend as well as an example API endpoint at `/api/hello`.

### Docker
A `Dockerfile` is provided for containerized deployments:
```bash
docker build -t myapp-backend ./backend
```

## Frontend

The `frontend` folder contains static files that can be customized. The layout uses Bootstrap and includes a responsive navbar and footer.

Open `frontend/index.html` directly in your browser or modify the EJS templates under `backend/views` if you render pages server-side.

## Customization
- Update **navbar links** and branding in `backend/views/layout.ejs` or `frontend/index.html`.
- Adjust styling in `frontend/css/styles.css` or `backend/public/styles.css`.

This setup aims to be lightweight yet extensible for most small to medium projects.
