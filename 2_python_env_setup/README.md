```bash
pip list --format=freeze > requirements.txt
conda create -n test_env python=3.10.0
pip install -r requirements.txt
```

```bash
pip install pipenv
pipenv install

pipenv install --dev pandas
pipenv install --dev seaborn
```
