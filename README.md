# NSHkr CMS

Modern headless CMS built with Elixir Phoenix, designed for content management and API-first architecture.

## Features

- **Headless Architecture**: API-first design for maximum flexibility
- **Phoenix Framework**: Built on robust Elixir/Phoenix foundation
- **Content Management**: Rich content creation and editing capabilities
- **API Endpoints**: RESTful and GraphQL APIs for content delivery
- **Multi-tenant**: Support for multiple sites/domains
- **Real-time**: Phoenix LiveView for real-time admin interface

## Architecture

- **Backend**: Elixir Phoenix (this repo)
- **Frontend**: Static sites powered by GitHub Pages
- **Database**: PostgreSQL
- **Cache**: Redis
- **Deployment**: Docker + Cloud hosting

## Quick Start

```bash
# Install dependencies
mix deps.get

# Setup database
mix ecto.setup

# Start server
mix phx.server
```

## API Documentation

- **REST API**: `/api/v1/*`
- **GraphQL**: `/api/graphql`
- **Admin Interface**: `/admin`

## Related Repositories

- [blog.nshkr.com](https://github.com/nshkr-factory-dot-ai/blog.nshkr.com) - First frontend implementation

