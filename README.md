# Florida Hotel Management System

A hotel management platform with a public website, online reservations,
staff operations, and secure payment processing.

## Architecture

- frontend/: React, TypeScript, and Vite
- backend/: Spring Boot microservices
- infrastructure/: Local development and monitoring configuration
- docs/: Requirements, architecture, and API documentation

## Development status

Initial repository and frontend setup completed.

## Security

- Never commit real credentials, API keys, or production secrets.
- Keep Chapa credentials exclusively on the backend.
- Route frontend API requests through the API Gateway.
- Use Keycloak for identity and access management.
