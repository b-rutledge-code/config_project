# Config Project

A Python-based configuration management system that includes:
- Credstash integration for secure credential management
- YAML-based configuration
- Configuration fetching and validation
- Optional requirements support

## Features
- Secure credential storage and retrieval
- YAML configuration parsing
- Configuration validation
- Flexible dependency management

## Setup
1. Install dependencies:
```bash
pip install -r requirements.txt
pip install -r optional-requirements.txt  # Optional dependencies
```

2. Configure your credentials and settings in `config.yaml`

## Usage
```python
from config import Config

config = Config()
# Access your configuration
```

## License
See LICENSE file for details.
