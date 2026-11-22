# Backend Engineering Skills

A collection of reusable AI Agent Skills for production-focused backend engineering.

Designed for Cursor, Claude Code, and other compatible AI coding agents.

## Available Skills

### Node.js Production

Production-focused guidance for:

- Async programming
- Error handling
- Graceful shutdown
- Performance
- Security
- Testing

### NestJS Production

Production-focused guidance for NestJS modules, validation, dependency injection, configuration, and HTTP APIs.

### Kafka Production

Production-focused guidance for Kafka producers and consumers, offsets, retries, duplicates, and shutdown.

## Installation

Install every skill:

```bash
npx skills add NITYES/backend-engineering-skills -a cursor
```

Install one skill:

```bash
npx skills add NITYES/backend-engineering-skills --skill nodejs-production -a cursor
npx skills add NITYES/backend-engineering-skills --skill nestjs-production -a cursor
npx skills add NITYES/backend-engineering-skills --skill kafka-production -a cursor
```

List the skills without installing them:

```bash
npx skills add NITYES/backend-engineering-skills --list
```

## License

MIT. See [LICENSE](LICENSE).
