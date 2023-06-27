# MERN-Project-place-app

MongoDB + Express + React + Node.js place app

<div align="left">
    <div style="display:flex; flex-direction:row;">
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white&style=flat">
        <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&style=flat">
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&style=flat">
        <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white&style=flat">
        <img src="">
    </div>
</div>
---

## Project Description

Based on Maximilian Schwarzmüller's Udemy course - https://www.udemy.com/course/react-nodejs-express-mongodb-mern/

MERN stack place app with google map api

---

## Includes

MongoDB, Express, React, Node.js, Google Geocoding API, Google Maps JavaScript API, JSON Web Token

---

## Development Period

2023.06.16 - 2023.06.27

---

### Development Environment

**Workspace** : Apple MacBook Air 2020 M1
**IDE** : Visual Studio Code
**MongoDB** : v6.0.6
**Express** : v4.18.2
**React** : v16.11.0
**Node.js** : v19.7.0

---

## Front-End .env configuration

In **development** it is necessary to have the following configuration in the **.env** file:

```env
{
    REACT_APP_GOOGLE_API_KEY=GOOGLE_API_KEY_VALUE
    REACT_APP_BACKEND_URL=BACKEND_URL/api
    REACT_APP_ASSET_URL=BACKEND_URL
}
```

---

## Back-End nodemon.json configuration

In **development** it is necessary to have the following configuration in the **nodemon.json** file:

```json
{
  "env": {
    "DB_USER": "MONGO_DB_USER",
    "DB_PASSWORD": "MONGO_DB_PASSWORD",
    "DB_NAME": "MONGO_DB_NAME",
    "GOOGLE_API_KEY": "GOOGLE_API_KEY_VALUE",
    "JWT_KEY": "JSONWebToken_KEY_VALUE",
    "PORT": "PORT_NUM"
  }
}
```
