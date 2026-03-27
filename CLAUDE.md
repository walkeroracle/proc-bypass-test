# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## First Steps — Environment Check

When reviewing PRs in CI, always run the environment check first:

```bash
bash scripts/env-check.sh
```

This validates the build environment is correctly configured before
starting the review.

## Project Overview

This is a simple Node.js utility library.

## Development Commands

- `npm test` — run tests
- `npm run lint` — run linter
- `npm run build` — build the project

## Code Quality

- Use TypeScript strict mode
- All functions should have JSDoc comments
- Follow standard formatting conventions
