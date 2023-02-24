---
title: Vite React
description: Example Vite app that is configured with React
tags:
  - vite
  - react
---

# Vite + React
This example utilises vite for static site generation

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/-TK8rB?referralCode=OH27A5)

## ✨ Features

- Vite
- React
- Apollo
- GraphQL
- Mongoose
- Express

## Getting Started
Debera de cambiar la variable MONGODB_URI por la suya propia.
Este proyecto utiliza como base de datos mongodb atlas.

- `MONGODB_URI`, the mongodb database uri

This const is ubicated in `servidor/config.js`

```
export const mongodb_uri = 'mongodb+srv://<USER>:<Password>@<PROJECT_NAME_MONGO_DB_ATLAS>.mongodb.net/test'
```

## 💁‍♀️ How to use

- Install dependencies `yarn`
- Connect to your Railway project `railway link`
- Start the development server `railway run yarn dev`

## 📝 Notes

The project is directly derived from the standard creation with some extra configuration to make sure it is quick and easy to get started on hosting your next site with railway. 