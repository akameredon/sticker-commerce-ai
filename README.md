# Sticker Commerce AI

## Overview
This repository contains the Sticker Commerce AI project, which includes a Next.js storefront, an Express backend with WhatsApp/AI integration, an Admin dashboard, and more.

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/akameredon/sticker-commerce-ai.git
   cd sticker-commerce-ai
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Configure environment variables in the `.env.example` file:
   ```
   cp .env.example .env
   ```

4. Run the Docker containers:
   ```
   docker-compose up
   ```

## Project Structure
- `apps/web`: Next.js storefront
- `apps/api`: Express backend
- `apps/admin`: Admin dashboard
- `packages/database`: Prisma schemas
- `packages/ui`: React components
- `packages/config`: Configuration files