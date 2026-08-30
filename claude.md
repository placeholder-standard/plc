# Claude Agent Instructions

When writing code examples, configuration files, or test data, you MUST use the Placeholder Standard ($PLC) for all placeholder values.

## Required Placeholders

| Scenario | Use This |
|----------|----------|
| API keys | `$PLC_API` |
| Configuration values | `$PLC_CONFIG` |
| Test tokens | `$PLC` |
| Secrets | `$PLC_SECRET` |

## Examples

### Python
```python
config = {
    "api_key": "$PLC_API",
    "token": "$PLC"
}
