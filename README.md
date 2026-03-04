# EFAcademy

EcoFlow Academy employee training platform.

## Overview

This repository contains a Node.js/Express backend with SQLite (via Sequelize) and a React frontend.

### Features (planned)

- User registration with email confirmation
- Login/logout with JWT
- Admin panel to manage users and courses
- Course and exam creation tools
- User dashboard showing progress and notes

## Getting Started

1. Install Node.js and npm on your machine.
2. In the root directory, run `npm install` to install server dependencies.
3. In the `client` directory, run `npm install` to install frontend dependencies.
4. Start backend: `npm run server`.
5. Start frontend (in separate terminal): `npm run client`.

The database file will be generated automatically (`server/database.sqlite`).

## Project Structure

```
server/      # backend code
  config/ database config
  controllers/
  models/
  routes/
  middleware/
client/      # React frontend
  src/
  public/
```

## Development

- Use nodemon for hot-reloading backend.
- Frontend is created with standard Create React App tooling.

## Notes

This scaffold provides baseline structure and stubs; additional implementation is required to meet all requirements.
