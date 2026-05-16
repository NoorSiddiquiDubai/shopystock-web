# AGENTS.md

## Cursor Cloud specific instructions

This is a minimal static HTML project consisting of a single `index.html` file. There are no build tools, package managers, linters, test frameworks, or external dependencies.

### Dev Server

To serve the project locally, use Python's built-in HTTP server:

```sh
python3 -m http.server 8000 --directory /workspace
```

The site is then available at `http://localhost:8000/`.

### Notes

- There is no build step, no linting configuration, and no test suite.
- No package manager or dependency installation is required.
- If dependencies or a build system are added in the future, update this file and the VM update script accordingly.
