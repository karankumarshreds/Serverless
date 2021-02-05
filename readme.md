# AWS serverless lambda

Servers will be managed by the AWS using its service **lamdba**.

### Disadvantages of traditional computing

- Manual provisioning of servers
- Risk of over-provisioning or under-provisioning of servers
- Calculating scaling of infrastructure
- Keeping the OS's and softwares updated

## API Key

Similar to how google apis provide an `api key` to send and retreive data from the apis.
We can create an `api-key` and use it from the client side to send the request to the API.

**Usage plan**: We can limit the number of requests for this key.

## Flow

1. Method Request

Used for prechecks of incoming requests like **Authorisation**, **Request validators**, **API key validation** etc

2. Integration Request

Decides how the incoming request will be handled. That's it. It triggers the component which will execute the logic.
**Note**: Does not execute any logic.

3. Integration Response

Extracts the data returned from the logic.

4. Method Response

We can set the status code and the structure of the final response.
