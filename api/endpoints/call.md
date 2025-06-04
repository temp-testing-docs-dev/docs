---
title: Call Endpoint
description: API endpoint for managing call operations in Vapi
---

# Call Endpoint

The Call endpoint provides comprehensive functionality for managing voice conversations through Vapi's API. This endpoint allows you to create, retrieve, update, and delete calls, as well as access detailed call information including costs, transcripts, and metadata.

## Overview

The Call endpoint supports standard REST operations and provides access to rich call data including:

- Call configuration and status
- Cost tracking and billing information
- Real-time call updates and events
- Assistant and customer interaction data
- Phone number and provider information

## Key Features

### Cost Tracking

Calls now include detailed cost information through the `costs` array, which tracks various expense types:

- **Knowledge Base Costs**: Track expenses related to knowledge base queries during calls through the new `KnowledgeBaseCost` type accessible via `call.costs[type=knowledge-base]`
- Standard call processing costs
- Provider-specific charges

### Enhanced Call Data

Recent updates have expanded the call schema to include:

- Comprehensive timestamp information
- Customer and assistant interaction details
- Phone number associations
- Call provider metadata

### Deprecated Fields

Please note that the following fields are now deprecated:

- `phoneCallProvider` - Use the updated provider configuration instead
- `phoneCallProviderId` - Replaced with improved provider identification

## Client Messages

The Call endpoint works in conjunction with various client message types that provide real-time updates:

- **Client Message Tool Calls**: Information about function calls made during conversations
- **Client Message Transcript**: Real-time transcription data
- **Client Message Speech Update**: Updates on speech processing and recognition
- **Client Message Transfer Update**: Notifications about call transfers

## Speech Endpointing

Calls support advanced speech endpointing configuration through:

- `smartEndpointingPlan`: Enhanced control over when the assistant should start and stop speaking
- `customEndpointingRules`: Define custom rules for speech timing
- Improved `waitFunction` in `LivekitSmartEndpointingPlan` for better call flow responsiveness

<Warning>
The `smartEndpointingEnabled` property in `StartSpeakingPlan` is now deprecated. Use `smartEndpointingPlan` or `customEndpointingRules` instead for controlling endpointing behavior.
</Warning>

## Speech Interruption Hooks

New webhook capabilities allow you to handle speech interruption events:

- **Speech Interrupted Assistant Hook**: Triggered when the assistant's speech is interrupted
- **Speech Interrupted Customer Hook**: Triggered when the customer's speech is interrupted

These hooks enable you to implement custom logic for handling interruptions and maintaining natural conversation flow.

## Usage Considerations

When working with the Call endpoint:

1. Monitor the `costs` array to track knowledge base usage and other expenses
2. Update any deprecated field usage in your applications
3. Leverage the enhanced endpointing features for better conversation control
4. Implement speech interruption hooks for improved user experience

The Call endpoint continues to evolve with enhanced features for cost tracking, speech management, and real-time communication capabilities.