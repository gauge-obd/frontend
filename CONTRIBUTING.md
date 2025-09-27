# Contributing to Gauge Frontend

First off, thank you for considering contributing to **Gauge Frontend** 🖤  
Contributions help us improve the project and move closer to making AI-powered automotive diagnostics accessible for everyone.  

---

## How to Contribute

- **Report bugs** by opening an [issue](../../issues).  
- **Suggest features** with clear explanations and use cases.  
- **Submit pull requests (PRs)** to improve the code, docs, or tests.  

Please make sure your contributions follow our coding standards and design philosophy: **clarity, simplicity, and accessibility.**  

---

## Prerequisites

Before you begin, ensure you have the following installed:  

- **`Node.js v20+`**  
- **`npm v10+`**  
- **`Git`**  
- A modern browser (`Chrome`, `Firefox`, `Edge`)  

Optional for testing:  
- An OBD-II adapter or simulated data source  

---

## Development Setup

**Fork the repo and clone your fork:**
   ```bash
   git clone https://github.com/your-username/frontend.git
   ```

   ```bash
   cd frontend
   ```
**Install dependencies:**

```bash
npm install
```
**Run the development server:**

```bash
npm run dev
```
The app will be available at `http://localhost:5173/` (*or as specified in your terminal*).

## Branching Strategy
main → stable, production-ready code

dev → active development

Feature branches should be named:

```arduino
feature/short-description
fix/short-description
docs/short-description
```

## Testing
We expect contributions to include tests where appropriate.

Run the test suite with:

```bash
npm test
```

*Add new tests for new features or bug fixes.*

## Code Style
Use Prettier for formatting.

Follow React + TypeScript best practices (if TS is used).

Keep components small, composable, and readable.

## Submitting a Pull Request
Make sure your branch is up to date with dev.

Ensure tests pass and code is formatted.

Open a pull request to dev with:

A clear title (e.g., feat: add new telemetry graph)

A description of changes and related issues.

## Community Guidelines
Be respectful and constructive.

Keep discussions technical and helpful.

Remember: Gauge is open-source, but safety-critical decisions always require professional diagnostics.

## License
By contributing, you agree that your contributions will be licensed under the MIT License.
