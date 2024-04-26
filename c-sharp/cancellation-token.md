# Cancellation Token
- a valuable tool for managing asynchronous operations, by propagating notifications that an operation should be canceled.
- In runtime, when an endpoint is called, the Token's value can be provided, enabling cooperative cancellation of asynchronous operations.
- CancellationTokenSource is responsible for creating a cancellation token and sending cancellation request to all copies of that token.

## CancellationToken Utilize
- helps conserve server resources, specially in scenarios where the task cancellation is necessary.

## Use Case
- User downloading a large file from your application
- Long running network request that could potentially hang due to network issues or slow servers.
- Background task 
- Concurency control

