# Plant Store Documentation

Documentation site for Plant Store, built with [Fern](https://www.buildwithfern.com/).

## Getting Started

### Prerequisites

- Node.js and npm
- [Fern CLI](https://www.buildwithfern.com/docs/cli): `npm install -g fern-api`

### Generate & Publish

From the repository root:

```bash
cd fern
fern generate --docs
```

This generates the documentation site. The published site is available at [hugo-nunez-demo.docs.buildwithfern.com](https://hugo-nunez-demo.docs.buildwithfern.com).

### Project Structure

```
fern/
├── docs/
│   ├── assets/       # CSS, fonts, images
│   └── pages/        # MDX content (landing, instructions)
├── openapi/          # API specification
├── docs.yml          # Site configuration
└── fern.config.json  # Fern project config
```

### Configuration

- **Organization:** Set in `fern/fern.config.json`
- **Site URL & styling:** Configured in `fern/docs.yml`
- **Custom CSS:** `fern/docs/assets/main.css`

## Features

- Styled landing page with hero section and feature cards
- API Reference with sandbox environment
- Webhook documentation (Plant Created)
- Python code samples for `POST /plant`
- Light and dark mode support
