# Wiremock Docker Demo
Project to accompany a series of blog posts on [Muya's Blog](https://blog.muya.co.ke/) on using Wiremock.

Check the series out here: [Using Wiremock to Mock API Responses: Part 1](https://blog.muya.co.ke/wiremock-response-templating/)

### Part 1: Using Wiremock to Mock API Responses
- Introduces Wiremock
- Demonstrates how to use Docker to set it up
- Mocks a sample API endpoint

### Part 2: Using Response Templating for Dynamic Responses
- Introduces response templating in Wiremock
- Shows how to enable it
- Shows how to use request parameters in the mocked response

## Running the Demo
This demo uses Docker to expose the mocked endpoints.

- Install [Docker](https://docs.docker.com/get-docker/)
- Run `docker-compose up`
```
docker-compose -f docker-compose.yml up
```

View all the available mocked API endpoints by going to http://127.0.0.1:8080/__admin/
