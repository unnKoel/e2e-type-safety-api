## Tech stack

- GraphQL Yoga
  GraphQL Server side
- Prisma
  ORM tool based on schema defination.
- Pothos schema builder
  A tool to generate GraphQL schema and keep sync with Prisma schema.

## Third-part services

- [railway](https://railway.app/)
  Using this service to bootstrap the postgresql database online.

- [Render](https://render.com/)
  Using this service to deploy both of static APPs and APIs

## What it aim to do

So the entire flow of types across your application will be as follows:

- Prisma will generate types based off of your database schema.
- Pothos will use those types to expose GraphQL types via an API.
- GraphQL Codegen will read your GraphQL schema and generate types for your frontend codebase  
  representing what is available via the API and how to interact with it.
