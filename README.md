# Aitindo Test - Backend

## Table of Content

- [Prerequisite](#Prerequisite)
- [Getting started](#Getting-started)
- [Build to production](#Build-to-production)
- [Troubleshooting](#Troubleshooting)

## Prerequisite

- NodeJS
- Laravel
- NextJS
- TailwindCSS

## Getting started

- Import database MYSQL change username with yours

- Start `Laravel` development server

  ```bash
  php artisan serve
  ```

  This will start a web server at `http://localhost:8000`

- Install dependencies

  ```bash
  npm install
  ```

- Start `Next` development server

  ```bash
  npm run dev
  ```

  This will start a web server at `http://localhost:3000`

## Build to production

- Build the `Next` app

  ```bash
  npm run build
  ```

  This will generate directory `.next`

## Troubleshooting

- Failed to install dependencies

  ```bash
  npm install --force
  ```
