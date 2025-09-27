[![CI](https://github.com/HeemalSyangbo/COMP3104/actions/workflows/ci.yml/badge.svg)](https://github.com/HeemalSyangbo/COMP3104/actions/workflows/ci.yml)

# COMP3104 – Developer Operations (Lab 04: Configuring CI)

This repo demonstrates a basic CI pipeline using **GitHub Actions** for a Node.js project.

## Repo Structure
- `.github/workflows/ci.yml` — CI workflow (checkout, setup Node, `npm install`, `npm test`)
- `package.json` — includes a placeholder test script

## Run locally
```bash
npm install
npm test
