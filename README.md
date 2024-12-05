# Google Books UI

## Description

A simple UI for consuming the Google Books API.

## Setup

- Ensure you are using PHP v8.3.9+.
- Ensure the following PHP extensions are enabled:
  - curl
  - fileinfo
  - mbstring
  - openssl
- Ensure you have a recent version of composer installed.
- `cd` into root directory.
- Create `.env` file and update params where necessary (e.g., API Key):
  ```bash
  cp .env.example .env
  ```
- Install dependencies:
  ```bash
  composer install
  ```

## Run Local

- `cd` into root directory.
- run local php server (from public directory):
  ```bash
  php -S 127.0.0.1:8000 -t ./public
  ```
- open link in brower

## Run Prod

- **_Do not run in a production environment!_**
