# QAAuto

A Python-based test automation framework for Quality Assurance testing.

## Overview

This repository contains automated tests for multiple testing layers:

- **API Tests** - Tests for GitHub API endpoints using the `requests` library
- **UI Tests** - Web UI automation tests using Selenium WebDriver with Page Object Model pattern
- **Database Tests** - SQLite database interaction tests for CRUD operations

## Project Structure

- `modules/` - Core modules with API clients, UI page objects, and database utilities
- `tests/` - Test suites organized by test type (api, ui, database)
- `config/` - Configuration files
- `conftest.py` - Pytest fixtures and test configuration
- `pytest.ini` - Pytest markers and settings

## Technologies

- **Python** - Primary programming language
- **Pytest** - Testing framework
- **Selenium WebDriver** - Browser automation
- **Requests** - HTTP library for API testing
- **SQLite** - Database for testing
