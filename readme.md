Laravel:

composer install
php artisan migrate
php artisan db:seed
php artisan serve

Vuejs:

npm install
npm run watch or npm run dev

# Viblo Resume Web

The web app is based in React.js

# Build Setup
Copy file `.env.example` to `.env`
```bash
    APP_URL=localhost:8000 (or cv.viblo.local:8000 with docker, ...)
    APP_BACKEND_DIR=../viblo-resume/public
```
```bash
# install dependencies
yarn install
# serve with hot reload
yarn dev
# build for production with minification
yarn build
```
