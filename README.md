# Python Advent Calendar

[![CI](https://github.com/CoefficientSystems/python-advent-calendar/actions/workflows/main.yaml/badge.svg)](https://github.com/CoefficientSystems/python-advent-calendar/actions/workflows/main.yaml)

Delivering gift-wrapped tutorials for the trendiest Python libraries right in your inbox :)

## Advent Calendar
  - **Day 1: Mastering Notifications with Python** – [newsletter](https://py-advent-calendar.beehiiv.com/p/py-advent-calendar-2023-day-1) – [notebook](advent/1_notifications/notebook.ipynb)

---

## CONTRIBUTING

### Contributors Cheatsheet
  - **pre-commit:** `pre-commit run --all-files`
  - **pytest:** `pytest` or `pytest -s`
  - **coverage:** `coverage run -m pytest` or `coverage html`
  - **poetry sync:** `poetry install --no-root --sync`
  - **updating requirements:** see [docs/updating_requirements.md](docs/updating_requirements.md)
  - **create towncrier entry:** `towncrier create 123.added --edit`

### Initial project setup

1. See [docs/getting_started.md](docs/getting_started.md) or [docs/quickstart.md](docs/quickstart.md)
   for how to get up & running.
2. Check [docs/project_specific_setup.md](docs/project_specific_setup.md) for project specific setup.
3. See [docs/using_poetry.md](docs/using_poetry.md) for how to update Python requirements using
   [Poetry](https://python-poetry.org/).
4. See [docs/detect_secrets.md](docs/detect_secrets.md) for more on creating a `.secrets.baseline`
   file using [detect-secrets](https://github.com/Yelp/detect-secrets).
5. See [docs/using_towncrier.md](docs/using_towncrier.md) for how to update the `CHANGELOG.md`
   using [towncrier](https://github.com/twisted/towncrier).
