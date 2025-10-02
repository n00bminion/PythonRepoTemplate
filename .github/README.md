To install the current project, run the followings:

### Create activate the virtual environemt
```console
cd <<your project root directory>>
python -m venv .venv
```
or
```console
cd <<your project root directory>>
py -m venv .venv
```

### Activate the virtual environemt
```console
.\.venv\Scripts\activate
```

### Install an editable version in the venv (allows for further code changes)
```console
pip install -e .
```

### Or install the project as a package (no further code changes)
```console
pip install .
```

