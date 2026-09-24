# quillstatic

Static blog generator: markdown in, tidy HTML out

Small but I use it weekly.

## Highlights

- Single template, plain str.format, no Jinja
- Index page with post list by date
- RSS feed generation
- Markdown posts with fenced code and tables

## Installation

```bash
pip install -r requirements.txt
```

## How to use

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
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Why

Needed this for myself; figured others might too.

## License

MIT licensed, see LICENSE.
