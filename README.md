# Fastify ESLint Rules
This repository contains a collection of custom ESLint rules for the Fastify web framework. These rules are intended to enforce best practices and help maintain a consistent codebase when building web applications with Fastify.

## Installation
To use these rules in your project, you will need to have ESLint and the eslint-plugin-fastify package installed. You can install them by running the following command:

```
npm install eslint eslint-plugin-fastify
```
Then add the plugin to your .eslintrc configuration file:

```json
{
  "plugins": ["fastify"],
  "rules": {
    "fastify/rule-name": "error"
  }
}
```
## Available Rules
The following rules are currently available in this plugin:

- `fastify-route-prefix`: enforces a specific prefix for all routes in the application.
- `fastify-route-validation`: enforces proper validation of request parameters and bodies for all routes in the application.
- `fastify-route-response`: enforces proper response handling for all routes in the application.
- `fastify-route-documentation`: enforces proper documentation of all routes in the application.
- `fastify-route-authentication`: enforces proper authentication and authorization handling for all routes in the application.
- `fastify-route-rate-limiting`: enforces rate limiting for all routes in the application.
- `fastify-logging`: enforces proper logging for all routes in the application.
- `fastify-error-handling`: enforces proper error handling for all routes in the application.
- `fastify-cors`: enforces proper handling of CORS (Cross-Origin Resource Sharing) headers for all routes in the application.
- `fastify-performance`: enforces best practices for performance optimization for all routes in the application.
- `fastify-middleware`: enforces proper use of middleware for all routes in the application.
- `fastify-schemas`: enforces the use of schemas to validate request payloads and responses.
- `fastify-pre-handler`: enforces the use of preHandler hooks to validate request headers and query parameters.
- `fastify-versioning`: enforces the use of versioning for the routes in the application.
- `fastify-route-grouping`: enforces the use of grouping of related routes.
- `fastify-request-id`: enforces the inclusion of request ids in the headers of all requests.
- `fastify-route-methods`: enforces the use of only allowed methods for each route.

## Contributing
We welcome contributions to this repository. If you have an idea for a new rule or have found a bug, please open an issue or submit a pull request.

## License
This repository is licensed under the MIT License.

## Star us on GitHub
If you find this repository useful, please consider starring us on GitHub. Your support helps us continue to maintain and improve this project.

## Credits
- `ChatGPT`: thanks to ChatGPT for this amazing README.md file
