## Running SCA

```bash
pip install -r requirements.txt
./sca.py --input-files=analyze-me.php
```

## Running the test suite
```bash
pip install -r requirements.txt
nosetests core/tests/ --ignore-files=.*samate.*
```

