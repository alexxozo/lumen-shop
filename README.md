# lumen-shop

## How to use
### Backend setup (backend directory)
You will need php and composer installed on your system.
1. Create a file named .env in the main directory with your database credentials. It should be identical to .env.example file.
2. Migrate the table for products to your database with:
```
php artisan migrate
```
3. Create some random entries with:
```
php artisan db:seed
```
4. Start the server with: 
```
php -S localhost:8000 -t public
```
### Frontend setup (frontend directory)
You will need npm and nodejs installed on your system.
1. Install all the packages needed with:
```
npm install
```
2. Start the server (at localhost:3000) with
```
node app.js
```

#### After these 2 setups you can acces localhost:3000.
