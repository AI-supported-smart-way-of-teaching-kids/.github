# Contributing guide (short)

- Run linters and tests locally before opening a PR:
  - Backend: `black .` `flake8 .` `pytest`
  - Frontend: `npm run format` `npm run lint` `npm test`
  - ML: `black .` `flake8 .` `pytest`

- Install pre-commit hooks:
  - Python: `pip install pre-commit && pre-commit install`
  - JS: `npm install` (plus husky if you use it)

- Use the CODEOWNERS to request the right reviewers; files under `/src/backend` will request `backend-team`.
