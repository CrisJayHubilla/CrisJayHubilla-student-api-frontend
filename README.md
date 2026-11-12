# Attendance Portal Frontend

Static HTML/CSS/JS page. No build step. Deploy on Vercel (or GitHub Pages).

## Setup
1. Deploy the backend first and note its URL, e.g. `https://my-backend.vercel.app`.
2. In `index.html`, replace `https://YOUR-BACKEND.vercel.app/api/attendance` with your backend URL + `/api/attendance`.
3. Push this folder as its own GitHub repo.
4. Vercel: Add New > Project > import the repo (Framework preset: Other). Redeploy after every push.

## Local
Run the backend locally, then open `index.html` (on localhost it uses http://localhost:3000/api/attendance automatically).

## API used
GET/POST `/api/attendance`, PUT/DELETE `/api/attendance?id=ID`.
