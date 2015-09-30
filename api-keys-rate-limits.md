# API keys and rate limits

## Obtain an API key

To use the Mapzen Search service, you must first obtain a free developer API key. Sign in at https://mapzen.com/developers to create and manage your API keys.

1. Go to https://mapzen.com/developers.
2. Sign in with your GitHub account. If you have not done this before, you need to agree to the terms first.
3. Create a new key for Mapzen Search, and optionally, give it a name so you can remember the purpose of the project.
4. Copy the key into your code.

## Rate limits
Because Mapzen Search is a free, shared service, there are limitations on the numbers of requests to prevent individual users from degrading the overall system performance.

Mapzen Search allows you a maximum of:
- 6 requests per second
- 30,000 requests per day

If you need more capacity, contact [search@mapzen.com](mailto:search@mapzen.com). You can also set up your own instance of [Pelias](https://github.com/pelias/pelias), which has access to the same data used in Mapzen Search.

## Security
Mapzen Search works over HTTPS, in addition to HTTP. You are strongly encouraged to use HTTPS for all requests, especially for queries involving potentially sensitive information, such as a user's location or search query.