# git-blame-ai-reviewer

![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Analyzes git history with AI to flag tech debt and suggest refactors.

## Overview

This tool provides a production-ready implementation focused on performance, security, and developer experience. Built with modern best practices and designed for real-world deployment.

## Features

- **High performance** — optimized for low latency and high throughput
- **Production ready** — proper error handling, logging, and observability
- **Well tested** — unit and integration tests included
- **Easy to deploy** — Docker support out of the box

## Installation

```bash
git clone https://github.com/abubakar-99/git-blame-ai-reviewer
cd git-blame-ai-reviewer
npm install
```

## Usage

```bash
npx ts-node src/index.ts
```

## Architecture

```
git-blame-ai-reviewer/
├── src/
│   ├── main.ts
│   ├── core/
│   └── utils/
├── tests/
├── docs/
├── Dockerfile
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
