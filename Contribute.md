# Contributing to SamyamLM

First off, thank you for considering contributing to SamyamLM! ❤️

## How Can I Contribute?

### Reporting Bugs

If you find a bug, please open an issue on GitHub with:

- A clear title and description
- Steps to reproduce the bug
- Expected behavior vs actual behavior
- Screenshots or code samples if possible

### Suggesting Features

Have an idea? Open an issue with:

- A clear description of the feature
- Why it would be useful for SamyamLM
- Any examples from other projects

### Pull Requests

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Run tests if available
5. Commit with clear message: `git commit -m "Add: feature description"`
6. Push to your fork: `git push origin feature/your-feature-name`
7. Open a Pull Request

## Development Setup

```bash
# Clone your fork
git clone https://github.com/your-username/SamyamLM-Indic-Geo-AI
cd SamyamLM-Indic-Geo-AI

# Install dependencies
pip install -r requirements.txt

# Run the annotator
python src/prelabeling/clip_annotator.py
