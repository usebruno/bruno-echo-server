# Bruno Echo Server

A simple HTTP server that echoes the request body and headers back to the client.

## Example
```bash
curl --request POST \
  --url https://echo.usebruno.com \
  --header 'content-type: application/json' \
  --data '{
  "bruno": "is-awesome",
  "long-int": 990531470713421825
}
```

## Development

```bash
npm install
npm start
```