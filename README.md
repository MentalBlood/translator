<h1 align="center">📜 translator</h1>

<h3 align="center">Translate PDF and generate sentencewise table</h3>

<p align="center">
<a href="https://github.com/MentalBlood/translator/blob/master/.github/workflows/lint.yml"><img alt="Lint Status" src="https://github.com/MentalBlood/translator/actions/workflows/lint.yml/badge.svg"></a>
<a href="https://github.com/MentalBlood/translator/blob/master/.github/workflows/typing.yml"><img alt="Typing Status" src="https://github.com/MentalBlood/translator/actions/workflows/typing.yml/badge.svg"></a>
<a href="https://github.com/MentalBlood/translator/blob/master/.github/workflows/complexity.yml"><img alt="Complexity Status" src="https://github.com/MentalBlood/translator/actions/workflows/complexity.yml/badge.svg"></a>
<a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
<a href="https://www.python.org/"><img alt="Python version: >=3.11" src="https://img.shields.io/badge/Python-3.11%20|%203.12-blue"></a>
</p>

## Installation

```bash
python3 -m pip install --upgrade git+https://github.com/mentalblood/translator
```

## Usage

```bash
cat some/paper.pdf | python3 -m translator -f html -l ru > paper_translated.html
```
