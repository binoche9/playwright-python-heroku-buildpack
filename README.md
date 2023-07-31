# playwright-python-heroku-buildpack

A Heroku buildpack for installing browsers for the Python version of Playwright.

## Usage

This build pack must be used *after* installing the Python dependencies (the `playwright` package in particular).

```
heroku buildpacks:set https://github.com/binoche9/playwright-python-heroku-buildpack.git -a my-app
```

## Environment variables

You can optionally use the `PLAYWRIGHT_BROWSERS_PATH` environment variable to control where the browsers get installed.
