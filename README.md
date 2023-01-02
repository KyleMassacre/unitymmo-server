# Unity3d Basic API Server
> Allows you to communicate with your Unity3d game using a rest API and a built-in Websocket server using Socket.io
> 
> This is using [AdonisJS](https://adonisjs.com) so if you have any questions, please consult the [docs](https://docs.adonisjs.com/guides/introduction)

## Installation
```
git clone https://github.com/KyleMassacre/unitymmo-server.git
```
If you are using NPM as your package manager:
```
npm install
```
Or if you are using Yarn:
```
yarn add
```
Please note, this is going to install the MySQL package byt default but if you wish to use something else:
- SQLite:
```
npm i sqlite3
```
- PostgreSQL
```
npm i pg
```
- OracleDB
```
npm i oracledb
```
- MSSQL
```
npm i tedious
```
Please remember to use your preferred package manager.

## Finalizing
```
cp .env.example .env
```
One last command to run would be to change your `APP_KEY` in your .env file
```
node ace generate:key
```

### Run your app:
```
node ace serve --dev
```
