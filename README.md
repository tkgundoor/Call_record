# Call Record Forensic

A simple Python project for parsing and analyzing call record logs.

## Features

- Parse call record CSV and JSON exports
- Identify suspicious call patterns
- Generate a summary report
- Command-line interface for quick forensic analysis

## Getting Started

1. Create a Python virtual environment:

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

2. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

3. Run the CLI:

```bash
python -m callrecord_forensic.cli parse --path sample_data/call_records.csv
```

## Project Structure

- `src/callrecord_forensic` - application code
- `tests` - unit tests
- `requirements.txt` - Python dependencies

## License

MIT
