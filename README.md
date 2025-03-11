# Setup ORT Server Client CLI (`osc`)

The `setup-osc` action provides an easy way to use the [ORT Server Client CLI](https://eclipse-apoapsis.github.io/ort-server/docs/getting-started/cli) in a GitHub workflow.

## Configuration

- `osc-version`: The version of `osc` to set up, defaults to `latest`.

### Authentication

`setup-osc` can also authenticate with the ORT Server instance using the following options:

- `base-url`: The base URL of the ORT Server instance.
- `token-url`: The URL to request a token for the ORT Server instance.
- `client-id`: The client ID to use for authentication.
- `username`: The username to use for authentication.
- `password`: The password to use for authentication.
