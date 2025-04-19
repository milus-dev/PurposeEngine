# Debug Entry 001 – Can't Run Script / "main not defined"

**Date**: 2025-04-18  
**Error**:
NameError: name 'main' is not defined

**Cause**: I typed `main()` without defining the `main()` function first.

**Fix**: Added:
```python
def main():
    print("Welcome to Purpose Engine")
main()

---

# Debug Entry 002 – Script won’t run / Python shell confusion

**Error**:
Typing `python` opened a `>>>` prompt and didn’t run my script.

**Cause**: I accidentally entered the Python interactive shell instead of running the file directly.

**Fix**: Exited shell with `exit` and ran the correct command:
```bash
python purpose_engine.py