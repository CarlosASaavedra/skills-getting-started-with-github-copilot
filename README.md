# Getting Started with GitHub Copilot

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey CarlosASaavedra!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/CarlosASaavedra/skills-getting-started-with-github-copilot/issues/1)

---

## Backend tests

This repository includes a backend test suite for the FastAPI application.

### Run the tests

From the project root, install dependencies and run:

```bash
pip install -r requirements.txt
pytest -q
```

### What is covered

- `tests/test_app.py` exercises the backend API using FastAPI's `TestClient`
- Includes signup and participant deletion flows
- Uses an `autouse` fixture to preserve in-memory activity state between tests

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

