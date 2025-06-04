---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our API endpoints and allows you to generate client libraries.

You can access the OpenAPI specification at:

https://api.vapi.ai/openapi.json

## CallController_create Operation

The `CallController_create` operation allows you to initiate a new outbound call. The summary for this operation has been updated to:

"Create a new outbound call with the specified parameters."

This operation takes the following parameters:

- `assistant_id`: The ID of the assistant to use for the call
- `to`: The phone number to call
- `from`: The phone number to call from 
- `options`: Additional optional parameters

It returns a Call object with details about the initiated call.

For full details on request and response formats, please refer to the OpenAPI specification.

## Using the OpenAPI Specification

You can use tools like Swagger UI or Redoc to visualize and interact with the API specification.

Many programming languages also have tools to generate client libraries from OpenAPI specs, allowing you to easily integrate Vapi into your applications.

For example, to generate a Python client:

```
openapi-generator generate -i https://api.vapi.ai/openapi.json -g python -o vapi-client
```

This will create a Python client library in the `vapi-client` directory.

## Getting Help

If you need any assistance using the OpenAPI specification or have any questions, please don't hesitate to reach out to our support team.