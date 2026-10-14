# Command Line Interface — LEGAL_BERT

**Upstream:** https://github.com/nicedoc/legal-bert

## Anticloud CLI

```bash
# Install
pip install anticloud-legal-bert

# Run offline with PAX inference
anticloud-legal-bert --offline --pax-local

# Run with AIOSS logging
anticloud-legal-bert --aioss-log ./ledger.jsonl

# Single binary (after build)
./legal_bert --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
