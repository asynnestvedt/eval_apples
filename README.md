# Orchard AI Microservice Challenge

## Introduction

In this challenge, you will design and develop a microservice that merges AI-driven technology with an apple orchard theme. Your task is to create a RESTful API, containerized with Docker, complemented by well-written tests and clear documentation.

### Key Requirements

- **Language**: Choose Golang, TypeScript, Java, or Rust.
- **API**: A single RESTful GET endpoint.
- **Docker**: Containerize the microservice.
- **Testing**: Implement at least one meaningful test.
- **Documentation**: Provide detailed instructions in `README.md`.

### The Challenge: AI & Apple Harvest API

Create a REST API with a single GET endpoint:

- **Endpoint**: `GET /apple-variety/{variety}`
  - **Response**: "This AI helps in the orchard. The characteristics of the apple variety '{variety}' are: {dynamic-response}."

  - **Dynamic-Response**: Customize the response based on the apple variety provided in the `variety` parameter (e.g., Honeycrisp, Granny Smith).

### Docker

- Provide a Dockerfile to containerize the service.
- Include instructions for building and running the container.

### Testing

- Write a test to verify the API's functionality.
- Include clear instructions to run the test in the documentation.

### Documentation

Your `README.md` should cover:

1. Setup instructions.
2. Design rationale.
3. Example usage of the API.

## Evaluation Criteria

- **Code Quality**: Clean, efficient, maintainable code.
- **Functionality**: The API performs as expected.
- **Testing**: The test should be relevant and well-structured.
- **Documentation**: Clear and concise, covering all necessary steps.

## Bonus: Track Popular Apple Varieties

### Additional Task

Track how many times each apple variety has been queried and store this information in a database. You can use MongoDB, PostgreSQL, SQLite, or another database.

- **Database**: Store the `variety` and the number of times it was queried along with timestamps.
- **Optional**: Add an endpoint to retrieve the most popular apple varieties.

### Documentation

Expand the `README.md` to include:

1. Database setup and integration.
2. (Optional) Documentation of the retrieval endpoint for popular apple varieties.

## Submission

- Host your code on a public platform (e.g., GitHub).
- Ensure the repository is accessible for review.
- Alternatively, zip and send your archive to the email provided during your interview.

