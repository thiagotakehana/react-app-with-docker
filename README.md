# React App with Docker

## What this project?

This project was created to show how a web react app can be deployed in Dev and Production mode with Docker

## How to run project

### Build and Run project

    # Start container
    docker-compose -f docker-compose.dev.yml up -d --build

    # Stop container
    docker-compose -f docker-compose.dev.yml down

You can use .dev or .prod files for each environment
