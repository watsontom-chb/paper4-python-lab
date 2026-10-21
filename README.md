# CAIE 9618 Paper 4 Python Lab

A browser-based practice app for original Python programming challenges across algorithms, data structures, programming concepts and object-oriented programming.

## Run locally

Open `index.html` in a modern browser. The **Run Python** feature loads Pyodide from a CDN, so an internet connection is needed for Python execution.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow that publishes the site whenever changes are pushed to `main`.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Open the **Actions** tab and check the `Deploy to GitHub Pages` workflow.
4. When deployment succeeds, the site will be available at:
   `https://watsontom-chb.github.io/paper4-python-lab/`

## Notes

- The answer checker is a keyword/pattern guide, not a full correctness grader.
- The Python runner executes submitted code in the user's browser through Pyodide.
- This is an independent practice resource, not an official Cambridge International product.
