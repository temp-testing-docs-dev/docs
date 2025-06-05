---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification file that describes our API endpoints, request/response structures, and authentication methods. This specification allows developers to easily integrate Vapi's functionality into their applications using a variety of tools and frameworks that support the OpenAPI standard.

## Accessing the OpenAPI Specification

You can access our latest OpenAPI specification at:

```
https://api.vapi.ai/api/v1/openapi.json
```

This JSON file contains the complete API definition and can be used with various OpenAPI tools for code generation, documentation, and testing.

## Key Features

Our OpenAPI specification includes:

- Detailed endpoint descriptions
- Request and response schemas
- Authentication methods
- Available API versions
- Supported data formats

## Using the OpenAPI Specification

Here are some ways you can utilize our OpenAPI specification:

1. **API Documentation**: Import the specification into tools like Swagger UI or ReDoc to generate interactive API documentation.

2. **Code Generation**: Use tools like OpenAPI Generator to create client libraries in various programming languages.

3. **API Testing**: Import the specification into tools like Postman or Insomnia for easy API testing and exploration.

4. **Server Stub Generation**: Generate server stubs for mock implementations or as a starting point for your own API.

## Example Usage

Here's a simple example of how you might use our OpenAPI specification with the Swagger UI tool:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vapi API Documentation</title>
    <link rel="stylesheet" type="text/css" href="https://unpkg.com/swagger-ui-dist@3/swagger-ui.css">
</head>
<body>
    <div id="swagger-ui"></div>
    <script src="https://unpkg.com/swagger-ui-dist@3/swagger-ui-bundle.js"></script>
    <script>
        window.onload = function() {
            SwaggerUIBundle({
                url: "https://api.vapi.ai/api/v1/openapi.json",
                dom_id: '#swagger-ui',
            });
        }
    </script>
</body>
</html>
```

This HTML file will render an interactive documentation of our API using Swagger UI.

## Versioning

Our OpenAPI specification is versioned to ensure backward compatibility. Always refer to the latest version for the most up-to-date API information.

## Support

If you encounter any issues with our OpenAPI specification or have questions about its usage, please contact our support team or refer to our [API documentation](https://docs.vapi.ai/api-reference) for more information.