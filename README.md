# Basic API routes example with docker

Next.js ships with [API routes](https://nextjs.org/docs/api-routes/introduction) which provides an easy solution to build your own `API`. This example shows how to create multiple `API` endpoints with serverless functions, which can execute independently.

## Deploy on your local maching

1. Clone the app
2. Install all the dependencies
```bash
npm i
```
3. Run the development server
```bash
npm run dev
```

## How to run the app in docker
1. Install docker on your maching via [Install Docker on Mac](https://docs.docker.com/desktop/install/mac-install/) 
2. Run next.js app with docker-compose
```bash
COMPOSE_DOCKER_CLI_BUILD=1 DOCKER_BUILDKIT=1 docker-compose build
```
3. To run Next.js with Docker and docker-compose you can then run

```bash
docker-compose up
```
4.  Hit http://localhost:3000 on your favorite browser after docker-compose up runs without any error

## References
1. How to use Next.js with Docker and [Docker](https://geshan.com.np/blog/2023/01/nextjs-docker/) compose a beginner's guide  ([Documentation](https://geshan.com.np/blog/2023/01/nextjs-docker/)).
