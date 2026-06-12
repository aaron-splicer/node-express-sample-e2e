# node-express-sample

Sample Node + Express app used by Splicer's real-Railway e2e test rotation (#1041).

- `GET /` — hello-world
- `GET /healthz` — liveness

**Do not delete.** Wired to `ClaudeApiRealRailwayIT.NODE_EXPRESS_STACK`.

## Local

```bash
npm install
npm start
```

## Docker

```bash
docker build -t node-express-sample .
docker run --rm -p 3000:3000 node-express-sample
```
