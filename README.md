# Automatic-Report-Generation
This code predict an automatic report for a given set of brain ct slices.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/sebaL27/Automatic-Report-Generation.git
cd Automatic-Report-Generation
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the automatic report generation system:
```bash
python main.py <path_to_ct_slices_directory>
```

Example:
```bash
python main.py ./data/ct_scans/
```

## Project Structure

- `main.py` - Main entry point for the application
- `requirements.txt` - Python dependencies
- `README.md` - Project documentation
- `LICENSE` - License information

## Features

- Load brain CT slices from a directory
- Analyze CT slices
- Generate automatic reports
- Save reports to file

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
