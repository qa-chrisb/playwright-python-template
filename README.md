# Playwright Python Template

## Overview

This repository provides a template for using Playwright with Python to write end-to-end tests for web applications. Playwright is a powerful library for browser automation, enabling fast and reliable testing.

## Features

- Cross-browser testing (Chromium, Firefox, WebKit)
- Headless and headed execution modes
- Easy integration with CI/CD pipelines
- Detailed test reports

## Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/qa-chrisb/playwright-python-template.git
    cd playwright-python-template
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Install Playwright browsers:
    ```bash
    playwright install
    ```

## Usage

Run tests using the following command:
```bash
pytest
```

To run tests in headed mode:
```bash
pytest --headed
```

## Folder Structure

- `tests/`: Contains all test files.
- `pages/`: Page Object Model (POM) implementation.
- `utils/`: Utility functions and helpers.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the Unlicense License. See the [LICENSE](LICENSE) file for details.
