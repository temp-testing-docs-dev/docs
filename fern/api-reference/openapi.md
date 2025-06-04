---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification that describes our REST API endpoints. You can use this specification to generate client libraries, explore the API, and more.

## Accessing the OpenAPI Specification

Our OpenAPI specification is available at:

```
https://api.vapi.ai/api/docs/openapi.json
```

You can use this URL to import the specification into API tools and documentation generators.

## Key Endpoints

Some of the key endpoints described in the OpenAPI spec include:

### Create a Call

```
POST /call
```

Creates a new outbound call or web call session.

Summary: Initiate a new call using the specified parameters. This can be used for outbound phone calls or web-based call sessions.

Parameters:
- `to`: The phone number or SIP address to call (for outbound calls)
- `from`: The phone number or SIP address to call from (for outbound calls) 
- `assistant_id`: ID of the Vapi assistant to use for the call
- `caller_id`: Optional custom caller ID to use
- `recording`: Enable/disable call recording
- `webhook_url`: URL to receive webhooks about call events
- `metadata`: Optional custom metadata to attach to the call

### Get Call Details 

```
GET /call/{call_id}
```

Retrieves details about a specific call by its ID.

### List Calls

```
GET /calls
```

Lists calls matching the specified filters.

## Using the OpenAPI Specification

You can use the OpenAPI specification to:

1. Generate client libraries in various programming languages
2. Import the API into tools like Postman for testing
3. Set up mock servers for development
4. Generate interactive API documentation

Many tools and frameworks support OpenAPI, allowing you to easily integrate Vapi's API into your development workflow.

## Versioning

The OpenAPI specification is versioned along with our API. Make sure to check for updates periodically to stay current with any API changes or new features.

For the latest updates and changes to our API, please refer to our [changelog](/changelog).