# mdfolio

Static blog generator: markdown in, tidy HTML out

## Highlights

- Markdown posts with fenced code and tables
- Single template, plain str.format, no Jinja
- Index page with post list by date
- RSS feed generation

## Getting started

```bash
pip install -r requirements.txt
```

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT licensed, see LICENSE.
