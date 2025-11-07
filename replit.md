# Laravel Application

## Overview
A Laravel 12.x PHP web application with SQLite database, running on PHP 8.2. This is a fresh Laravel installation with the default welcome page and example routing.

## Recent Changes
- **2025-11-07**: Initial Laravel application setup
  - Installed PHP 8.2 and Composer
  - Created Laravel 12.37.0 project
  - Configured SQLite database with default migrations
  - Set up Laravel development server on port 5000
  - Auto-generated application key and initial .env configuration

## Project Architecture

### Tech Stack
- **Backend**: Laravel 12.x (PHP 8.2)
- **Database**: SQLite (configured in .env)
- **Development Server**: Laravel Artisan serve
- **Package Manager**: Composer 2.7.7

### Directory Structure
- `app/` - Application core (Models, Controllers, Services)
- `routes/` - Web routes, API routes, console commands
- `resources/views/` - Blade templates
- `database/` - Migrations, seeders, factories
- `public/` - Public assets and index.php entry point
- `config/` - Configuration files
- `storage/` - Application storage (logs, cache, uploads)
- `tests/` - PHPUnit tests

### Key Features
- MVC architecture with Blade templating
- Database migrations already run (users, cache, jobs tables)
- Session and cache configured to use database
- Queue system configured
- PHPUnit testing framework included

## Running the Application

The Laravel development server runs automatically via the workflow:
```bash
php artisan serve --host=0.0.0.0 --port=5000
```

## Environment Configuration

The `.env` file contains:
- Application key (auto-generated)
- SQLite database configuration
- Session and cache settings
- Development mode enabled

## Next Steps

Potential enhancements:
- Add PostgreSQL database for production use
- Create custom controllers and models
- Build out custom views with Blade templates
- Implement authentication system
- Add API routes
- Configure email services
- Add form validation
- Create middleware for request processing

## User Preferences
No specific preferences set yet.
