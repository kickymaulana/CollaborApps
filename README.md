# Collabor Apps

Realtime collaboration web based application built with Laravel 8 & Nuxt. Communicate with message & voice realtime.

### Image Preview

![Example Collaborapps](https://user-images.githubusercontent.com/53980548/151662579-218da4f3-df7c-432f-916b-f7f1fe522275.png)

## Installation

### Backend Installation

- Clone BE repo [ssh or https]

```
git clone git@github.com:WailanTirajoh/CollaborApps-Backend.git
```

- Change directory to folder

```
cd collaborapps-backend
```

- Copy .env.example to .env

```
cp .env.example .env
```

- Create database [mysql or pgsql]

```
mysql -u <username> -p
create database 2022_collaborapps;
```

- Fresh Migrate DB

```
php artisan migrate:fresh --seed
```

- serve server & websocket server

```
// install dependency
composer install

// generate backend key
php artisan key:generate

// open 2 terminal on backend directory and run
// on terminal 1
php artisan serv

// on terminal 2
php artisan websockets:serv
```

### Frontend Installation

- Clone FE repo [ssh or https]

```
git clone git@github.com:WailanTirajoh/CollaborApps.git
```

- Change directory to folder

```
cd collaborapps
```

- Install dependency / package

```
npm i
```

- Serv app

```
npm run dev
```

### Login

- user 1:

```
email: examplea@example.com
password: password
```

- user 2:

```
email: exampleb@example.com
password: password
```
