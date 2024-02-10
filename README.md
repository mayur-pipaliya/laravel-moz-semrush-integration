# SEMrush and Moz API Integration Demo

This project showcases the integration of SEMrush and Moz APIs to retrieve and display data related to SEO and website analytics.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Integration with SEMrush API for SEO data
- Integration with Moz API for website analytics
- Display of combined data for comprehensive insights
- Simple and user-friendly interface

## Requirements

- PHP >= 8.1
- Laravel >= 10
- Composer
- SEMrush API key
- Moz API key

## Installation
1. Install dependencies:

   ```bash
   cd semrush-moz-api-demo
   composer install
   ```

2. Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env
   ```

3. Configure your SEMrush and Moz API keys in the `.env` file:

   ```dotenv
   SEMRUSH_API_KEY=your-semrush-api-key
   MOZ_API_KEY=your-moz-api-key
   ```

4. Run migrations:

   ```bash
   php artisan migrate
   ```
   
## Usage

1. Start the Laravel development server:

   ```bash
   php artisan serve
   ```

2. Access the application in your web browser at `http://localhost:8000`.

3. Enter the required inputs or parameters for SEMrush and Moz API requests.

4. View the displayed data and insights on the web interface.

