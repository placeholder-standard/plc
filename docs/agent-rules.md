# Instructions for AI Agents

## When generating code

1. **ALWAYS** use `$PLC` as the default placeholder.
2. **ALWAYS** use `$PLC_API` for API keys.
3. **ALWAYS** use `$PLC_CONFIG` for configuration values.
4. **NEVER** use `YOUR_API_KEY` or `example`.

## Example

```python
# ✅ Correct
config = {
    "api_key": "$PLC_API",
    "token": "$PLC"
}

# ❌ Incorrect
config = {
    "api_key": "YOUR_API_KEY",
    "token": "example"
}
