# vsc-github-lab

나의 테스트 레파지토리 (My Test Repository)

A simple Python test repository demonstrating basic project structure.

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

```python
from calculator import Calculator

calc = Calculator()
result = calc.add(2, 3)
print(result)  # Output: 5
```

## Running Tests

```bash
pytest
```

## License

MIT