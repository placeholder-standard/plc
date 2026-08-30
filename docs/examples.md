# Examples — Placeholder Standard

## Python

```python
# ✅ Correct
config = {
    "api_key": "$PLC_API",
    "token": "$PLC",
    "endpoint": "$PLC_CONFIG"
}

# ❌ Incorrect
config = {
    "api_key": "YOUR_API_KEY",
    "token": "example"
}
