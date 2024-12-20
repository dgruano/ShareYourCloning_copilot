# Share Your Cloning Copilot

## Overview
Share Your Cloning Copilot is a project designed to serve as a molecular cloning companion within the open source cloning app [ShareYourCloning](https://shareyourcloning.org)

For now, it utilizes the Wit.ai, natural language processing platform to interpret user requests and generate SYC sources with the appropriate data model structure.

Share Your Cloning Copilot is currently under heavy development

## Installation

### Prerequisites
- Python 3.12 or higher
- Poetry for dependency management

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ShareYourCloning_copilot
   ```

2. Install dependencies using Poetry:
   ```bash
   poetry install
   ```

3. Install pre-commit hooks:
   ```bash
   poetry shell
   pre-commit install
   ```

4. Create a `creds.json` file in the root directory with your Wit.ai access token:
   ```json
   {
       "wit_access_token": "YOUR_WIT_ACCESS_TOKEN"
   }
   ```
