---
title: MERN APPLICATION
description: Example Vite app that is configured with React
tags:
  - Vite
  - React
  - Apollo
  - GraphQL
  - Mongoose
  - Express
  - Cors
  - NodeJS
---

## ✨ Features

- Mongoose
- Express
- React
- NodeJS
- Vite
- Apollo
- GraphQL
- Cors

## Getting Started
Debera de cambiar la variable MONGODB_URI por la suya propia.
Este proyecto utiliza como base de datos mongodb atlas.

- `MONGODB_URI`, the mongodb database uri

This const is ubicated in `servidor/config.js`

```
export const mongodb_uri = 'mongodb+srv://<USER>:<Password>@<PROJECT_NAME_MONGO_DB_ATLAS>.mongodb.net/test'
```

## Instalation
Primero clonamos el repositorio git:
```
git clone https://github.com/j03rul4nd/MERN-APP.git
```
Run Backend
```
npm run dev
```
response:
```
🌐 Server ready at http://localhost:4000/graphql
🛰️  Mongo DB Connected test
```
Por defecto el GraphQL se ubicara en esta url:

- `URI`: http://localhost:4000/graphql

### Run Fronted
```
cd vite-project
npm run dev
```
response:
```
   VITE v4.1.1  ready in 727 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```
The `app mern` is ubicated for default in http://localhost:5173/

## 💁‍♀️ How to use

- Install dependencies `yarn`
- Connect to your Railway project `railway link`
- Start the development server `railway run yarn dev`

## 📝 Notes

The project is directly derived from the standard creation with some extra configuration to make sure it is quick and easy to get started on hosting your next site with railway. 