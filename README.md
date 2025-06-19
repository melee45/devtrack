# DevTrack Monorepo

This repository contains both the frontend (Next.js) and backend (NestJS) applications for DevTrack.

---

## Project Structure

```
.
├── client/   # Next.js frontend
├── server/   # NestJS backend
├── package.json
├── pnpm-lock.yaml
└── ...
```

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [pnpm](https://pnpm.io/) (recommended)

### Install Dependencies

From the root directory, run:

```bash
pnpm install
```

---

## Running the Applications

### Client (Next.js)

```bash
cd client
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

### Server (NestJS)

```bash
cd server
pnpm run start:dev
```

The server will start on [http://localhost:3001](http://localhost:3001) (or your configured port).

---

## Scripts

- `pnpm install` — Install all dependencies for both apps.
- `cd client && pnpm dev` — Start the Next.js frontend in development mode.
- `cd server && pnpm run start:dev` — Start the NestJS backend in development mode.

---

## Testing

### Client

```bash
cd client
pnpm test
```

### Server

```bash
cd server
pnpm run test
```

---

## Deployment

- **Client:** See [client/README.md](client/README.md)
- **Server:** See [server/README.md](server/README.md)

---

## License

MIT
