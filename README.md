# TypeScript-OOP

## Express API

The Express API, including its routes and server startup, is in
`src/app.ts`.

```bash
npm install
npm run dev
```

The development server listens on port `3000` by default. Set `PORT` to use a
different port. Available endpoints:

- `GET /` — API welcome message
- `GET /api/health` — health check

Build and run the compiled server with:

```bash
npm run build
npm start
```
