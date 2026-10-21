# work-sample-1
Monorepo application for the hospitality industry to manage tables, digital menus, customer orders, messaging, and venue administration in real-time.

Core components

API server (apps/api)

Built with TypeScript, it provides an API for business logic, authentication, WebSocket connections for real-time kitchen notifications, and push notifications. The application also supports SMS notifications via multiple channels.

Database

The application uses Prisma as an ORM and supports PostgreSQL, CockroachDB, SQLite, MySQL as a database. It also provides advanced options such as migrations and Prisma Postgres, or different driver adapters. All the database-related files are stored in the database directory.

Storage

The application can be deployed with Docker support (Dockerfile) and provides file upload functionality for AWS S3, Cloudflare R2, or local storage.

Main features

Orders and finance

This feature helps manage orders, process payments, calculate delivery costs, and view money-related information in real-time.

Menu and discovery

It provides digital menu options for customers with catalog customization and discovery features such as food modifiers, price rules, and venue-level variations.

Hotels and customers

The option helps manage multi-venue hotel configurations, assign staff, manage guest access, communicate with customers, and much more.

AI/Agent

The application is prepared to use various AI agents and provides development tools such as skills (.agents/skills/) to simplify Prisma database operations and make day-to-day database maintenance easier.
