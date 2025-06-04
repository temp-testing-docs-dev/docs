---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints, request/response formats, and available operations. This page contains information about how to access and use the OpenAPI specification.

## Accessing the OpenAPI Specification

You can access the Vapi OpenAPI specification at:

```
https://api.vapi.ai/openapi.json
```

This JSON file contains the full API definition in OpenAPI 3.0 format.

## Using the OpenAPI Specification

The OpenAPI specification can be used to:

1. Generate client libraries in various programming languages
2. Set up API testing and validation
3. Create interactive API documentation
4. Configure API gateways and proxies

## Key Operations

Some of the key operations defined in the OpenAPI spec include:

### CallController_create

This operation allows you to create a new call. The updated summary for this operation is:

"Create a new call with specified parameters including recipient, caller ID, and assistant configuration."

This operation accepts parameters such as the phone number to call, the caller ID to use, and settings for the AI assistant that will handle the call.

### AssistantController_create 

Creates a new AI assistant with the specified configuration.

### PhoneNumberController_list

Retrieves a list of phone numbers associated with your Vapi account.

## OpenAPI Tools

There are many tools available that can work with OpenAPI specifications:

- [Swagger UI](https://swagger.io/tools/swagger-ui/): Visualize and interact with your API's resources without having any of the implementation logic in place
- [OpenAPI Generator](https://openapi-generator.tech/): Generate clients, server stubs, and documentation from OpenAPI 3.0 definitions
- [Postman](https://www.postman.com/): Import OpenAPI specs to create collections and test API endpoints

## Versioning

The Vapi API follows semantic versioning. Any breaking changes to the API will result in a new major version of the OpenAPI specification.

## Support

If you encounter any issues with the OpenAPI specification or have questions about its usage, please contact our support team.