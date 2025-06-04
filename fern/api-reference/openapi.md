---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

The OpenAPI specification for the Vapi API is available at:

```
https://api.vapi.ai/api/openapi.json
```

You can use this specification to generate client libraries, explore the API, and more.

## Key Operations

### Create Call

Endpoint: `POST /call`

Creates a new outbound call.

Summary: Create a new call to a phone number or SIP address.

Parameters:
- `to` (required): The phone number or SIP address to call
- `from` (optional): The phone number or SIP address to call from
- `assistantId` (required): The ID of the assistant to use for the call
- `webhookUrl` (optional): A URL to receive webhooks about call events
- `recordingEnabled` (optional): Whether to record the call
- `timeout` (optional): How long to wait for the call to be answered

Example request:

```json
{
  "to": "+15555555555",
  "assistantId": "asst_123abc",
  "recordingEnabled": true
}
```

### Get Call

Endpoint: `GET /call/{callId}`

Retrieves details about an existing call.

Parameters:
- `callId` (path, required): The ID of the call to retrieve

### List Calls

Endpoint: `GET /call`

Lists existing calls.

Parameters:
- `limit` (query, optional): Maximum number of results to return
- `offset` (query, optional): Number of results to skip

### Update Call

Endpoint: `PATCH /call/{callId}`

Updates an existing call.

Parameters:
- `callId` (path, required): The ID of the call to update
- Request body: Call properties to update

For the full OpenAPI specification with all available endpoints and schemas, please refer to the JSON file linked above.