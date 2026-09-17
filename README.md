# First Game

A game development project.

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- Python >= 3.10
- Git

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd first-game

# Install Node.js dependencies
npm install

# Install Python dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env
```

### Development

```bash
npm run dev
```

### Testing

```bash
npm test
```

### Linting

```bash
npm run lint
```

## Project Structure

```
├── src/              # Source code
│   ├── api/          # API routes/endpoints
│   ├── models/       # Data models
│   ├── services/     # Business logic
│   └── utils/        # Utility functions
├── tests/            # Test files
│   ├── unit/         # Unit tests
│   └── integration/  # Integration tests
├── config/           # Configuration files
├── scripts/          # Build/utility scripts
├── docs/             # Documentation
└── .github/          # GitHub Actions workflows
```

## License

MIT
