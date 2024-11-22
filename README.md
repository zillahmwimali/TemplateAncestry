# Form Ancestry 101

A Rails application demonstrating form handling with ancestry gem and styled with Tailwind CSS.

## Prerequisites

- Ruby 3.3.0 or higher
- Rails 8.0.0
- Node.js and Yarn
- Foreman (will be installed automatically)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone git@github.com:zillahmwimali/Form-ancestry101-.git
   cd Form-ancestry101-
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Set up the database:
   ```bash
   rails db:create
   rails db:migrate
   ```

4. Start the development server:
   ```bash
   bin/dev
   ```
   This will:
   - Clean up any stale server.pid files
   - Kill any process using port 3000
   - Start the Rails server using Foreman

## Features

- Slim template engine for views
- Tailwind CSS for styling
- Ancestry gem for hierarchical data
- Foreman for process management

## Technology Stack

- Ruby 3.3.0
- Rails 8.0.0
- Slim templating engine
- Tailwind CSS
- Ancestry gem for tree structures
- SQLite3 database

## Development

The application uses:
- `slim-rails` for templating
- `tailwindcss-rails` for styling
- `ancestry` for hierarchical relationships
- `foreman` for process management

## Directory Structure

Key directories and files:
- `app/views/layouts/` - Layout templates
- `app/views/home/` - Home page views
- `config/routes.rb` - Application routes
- `Procfile.dev` - Foreman process configuration

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
