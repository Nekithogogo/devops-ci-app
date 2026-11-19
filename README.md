# devops-ci-app

Учебное Flask-приложение для практической работы № 10.
CI: Pylint → pytest → Docker build → smoke-test → GHCR.
Публикация выполняется только из `main`; в Pull Request проходят проверки без push.

- health endpoint: `/health`;
- образ: `ghcr.io/nekithogogo/devops-ci-app`;
- основной workflow: `.github/workflows/ci.yml`.
