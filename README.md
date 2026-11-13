# devops-ci-app

Чугунов К. Н., ЭФБО-11-24. Практическая работа №10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.
Публикация образа выполняется только из `main`. В Pull Request выполняются проверки без push.

- health endpoint: `/health`;
- образ: `ghcr.io/ch-kost/devops-ci-app`;
- основной workflow: `.github/workflows/ci.yml`.
