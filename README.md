# Product Service - REST API for product catalog

## Overview

REST API to manage product inventory for the e-commerce. 

## Prerequisites

- Node.js 18+
- npm 9+
- PostgreSQL 14+
- Docker

## Deployment

clone repo: `git@github.com:pabloher95/ecommerce_products.git`

### local deployment

- intialize npm configs: `npm install`

### containerized deployment

- build container from image

## Environment setup

Use env.example to configure environment variables, making sure to change default values to desired custom configuration

## API endpoints

GET `/products`: list all products
GET `/products/:id`: get product by ID
POST `/products/`: create products


## Contributions

As per GitFlow standards (see [docs/git_flow.md](docs/git_flow.md) for details):

- `main` and `develop` branches are read-only
- contributors working on new features should branch from `develop` branch using the `feature/*` naming convention and submit a pull request to merge to `develop`
- contributors working on packaging releases should branch from `develop` branch using the `release/*` naming convention and submit a pull request to merge to `main` and `develop`
- contributors working on fixing a bug in live deployment should branch off from `main` branch using the `hotfix/*` naming convention and submit a pull request to merge to `main` 