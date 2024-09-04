# Python Environment Setup
This repository helps candidates set up their machines before the technical stage of their interview. The pairing exercise requires screen sharing and a working `Python` environment with `Pytest` installed.

## Requirements
All of our Python exercises require the following dependencies to be installed and configured:

* Python (version 3.8 or higher)
* Pytest (version 6.0 or higher)

## Instalation
Please ensure that your Python version meets our expectations:
```bash
python --version
```

If you have an older version, please update Python by following the instructions here:
https://www.python.org/downloads/

### Pytest
Please ensure that your Pytest version meets our expecations:
```bash
pytest --version
```

If you have an older version, please update Pytest by following the instructions here:
https://docs.pytest.org/en/stable/getting-started.html#get-started

## Validation
You can validate your setup by navigating to the `setup` folder and running:
```
pytest .
```

Output:
```
❯ pytest .
==================================================================== test session starts =====================================================================
collected 1 item

test_setup.py .                                                                                                                                        [100%]

===================================================================== 1 passed in 0.00s ======================================================================
```
