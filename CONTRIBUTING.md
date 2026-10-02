# Contributing to SQLiteLens

Thanks for your interest in SQLiteLens.

## Development setup

```bash
git clone https://github.com/bafnayeygian/SQLiteLens.git
cd SQLiteLens
python -m pip install .
```

Run tests:

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## Contribution ideas

- HTML reports
- CSV export
- duplicate-index detection
- migration diff reports
- database comparison mode
- dbstat support
- query-plan helpers
- row sampling

## Pull requests

Keep changes focused and include tests for behavior changes.
