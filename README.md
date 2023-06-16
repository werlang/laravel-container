# Laravel Container

This is a sample for building a Laravel project within a container.

## Getting Started

To build and run the container, use the following commands:

```bash
docker compose up
```

## How?

The first time you run the container, it will build the image and install all the dependencies.

A Laravel project is created in the `app` directory. 

Run `docker compose up` again to start the container.

## .env

Don't forget to update the `.env` file with your database credentials. A sample `example.env` file is provided.