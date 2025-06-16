Dirty, but works ~~(on my machine)~~, at least.

```shell
# Ubuntu 24.04
# I'm using CUDA 12.9
apt install pipx
pipx install poetry
poetry install
poetry run pip install -r requirements.txt
poetry run python infer-web.py
```

