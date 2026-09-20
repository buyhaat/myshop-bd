# MyShop BD

MyShop BD is the rebuild of the supplied storefront with the existing frontend retained and a new backend/admin foundation.

## Structure
- `frontend/` existing storefront UI/assets
- `backend/` Express + SQLite API foundation
- `admin/` first admin dashboard foundation
- `database/` relational schema blueprint

## Local backend
```bash
cd backend
cp .env.example .env
npm install
npm start
```
API: `http://localhost:5000/api/health`

Open `admin/index.html` in a browser after the API is running.

## Branding
Brand: **MyShop BD**
Brand mark: **M**
