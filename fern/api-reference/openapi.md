---
title: OpenAPI
slug: api-reference/openapi
---

# OpenAPI

Vapi provides an OpenAPI specification for its API. This specification allows developers to understand and interact with the Vapi API in a standardized way.

## Accessing the OpenAPI Specification

You can access the Vapi OpenAPI specification at the following endpoint:

```
https://api.vapi.ai/openapi.json
```

## Recent Updates

The OpenAPI specification has been recently updated to reflect changes in the API. Specifically:

- The summary of the '/call' POST endpoint has been updated from 'YAKA' to 'Create Call'. This change provides a clearer description of the endpoint's purpose.

## Using the OpenAPI Specification

Developers can use this specification to:

1. Generate client libraries in various programming languages
2. Create interactive API documentation
3. Set up automated testing
4. Configure API gateways and other tools that support OpenAPI

## Example Usage

Here's an example of how you might use the OpenAPI specification to create a call using the updated '/call' endpoint:

```javascript
const axios = require('axios');

async function createCall() {
  try {
    const response = await axios.post('https://api.vapi.ai/call', {
      // Call parameters here
    }, {
      headers: {
        'Authorization': 'Bearer YOUR_API_KEY'
      }
    });
    console.log('Call created:', response.data);
  } catch (error) {
    console.error('Error creating call:', error);
  }
}

createCall();
```

## Staying Updated

As Vapi continues to evolve its API, the OpenAPI specification will be updated to reflect these changes. It's recommended to regularly check the specification for any updates that might affect your integration.

For more information on how to use the Vapi API, please refer to our [API Reference](/api-reference) documentation.