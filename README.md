# TTU-pax-romana-church-management-system
# TTU Pax Romana Church Management System

A Laravel 10+ church management system for Pax Romana (Takoradi Technical University).

This repository contains the custom application code (models, controllers, views, migrations, seeders, services, config) needed to add Pax Romana CMS features into a fresh Laravel installation.

## Quick setup (local)

1. Create a fresh Laravel app or clone this repo into a Laravel project root.
2. Copy these files into the Laravel app (overwrite or merge where appropriate).
3. Run:
   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   npm install
   npm run dev
   php artisan migrate --seed
   php artisan storage:link
   php artisan serve
