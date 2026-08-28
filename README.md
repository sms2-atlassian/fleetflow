# sri-test-repo

A demo repository used for testing and showcasing project workflows and tooling integrations.

---

## What the project does

This repository serves as a sandbox and demonstration project for validating CI/CD pipelines, repository guidelines, and integration workflows.

## Why it exists

It provides a controlled environment to trial new tooling, test automation scripts, and demonstrate best practices without affecting production systems.

---

## Prerequisites

- Git installed on your machine
- [Node.js](https://nodejs.org/) (or the relevant runtime for your environment)
- Access to the repository (clone permissions)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sms2-atlassian/sri-test-repo.git
   ```
2. Navigate into the project directory:
   ```bash
   cd sri-test-repo
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the application:
   ```bash
   npm start
   ```

---

## Usage

Run the following command to execute the main script:

```bash
npm run start
```

---

## Project structure

```
sri-test-repo/
├── README.md        # Project documentation
└── ...              # Additional source files and configuration
```

---

## Tests

Run the test suite with:

```bash
npm test
```

---

## Configuration

- Environment variables can be set in a `.env` file at the project root.
- Copy `.env.example` to `.env` and fill in the required values before running the app.
- Key configuration options:
  - `PORT` — the port the application listens on (default: `3000`)
  - `NODE_ENV` — environment mode (`development`, `test`, or `production`)

---

## Deployment

1. Ensure all tests pass before deploying:
   ```bash
   npm test
   ```
2. Build the project (if applicable):
   ```bash
   npm run build
   ```
3. Deploy to your target environment using your preferred CI/CD pipeline or hosting provider.
4. Tag the release in Git:
   ```bash
   git tag -a v1.0.0 -m "Release v1.0.0"
   git push origin v1.0.0
   ```

---

## Contributing

- Fork the repository and create a feature branch from `main`.
- Follow the existing code style and naming conventions.
- Write or update tests to cover your changes.
- Open a pull request with a clear title and description of what was changed and why.
- All pull requests require at least one approving review before merging.

---

## License and support

This project is for internal/demo use. For questions or support, contact the repository owner via GitHub issues or your organisation's internal support channel.
