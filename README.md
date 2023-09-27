# PHP developer recruitment task

## Description
Imagine that a customer approached you with a request to create a simple service for importing a list of products from a CSV file and enabling basic product management. They provided you with the following CSV file (sample_products.csv) containing a sample list of products.

Your task is to create a straightforward solution, a service written in PHP 8.2, and using the latest version of the Symfony framework or its components.

## Requirements
- Have a CLI command for data import from a local CSV file or a file from a remote location, depending on the URL provided by the user.
- Implement CLI commands for CRUD (Create, Read, Update, Delete) operations on products.
- Implement CRUD endpoints (API) for product management using REST and JSON. Apply pagination and the ability to filter products on collection endpoints.
- Emit events in JSON format to a RabbitMQ queue when adding a new product, updating an existing one, or deleting a product.
- Develop unit and integration tests for the solution.
- Create API documentation in the OAS (Swagger) format using the NelmioApiDocBundle library.
- Prepare a development environment using docker-compose.

**Bonus:**
- Prepare a consumer to consume the produced events.
- Create a CI (Continuous Integration) configuration file for a CI/CD (Continuous Integration/Continuous Deployment) system you are familiar with, including the build and application testing stages.


## Guidelines
- Remember about SOLID and Clean Code principles that you are familiar with
- You can either create a completely custom solution or make use of open-source libraries available on the internet.
- Place the created solution in a GitHub repository and share the repository link with our HR team
- If you encounter any challenges along the way, please add a comment detailing the biggest issue.


_Good luck!_

_co.brick team_
