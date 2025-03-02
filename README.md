# Common Ground Electronics Docs

These docs are published at https://docs.cgnd.dev

## Development

Install `uv` by following the instructions at https://docs.astral.sh/uv/getting-started/installation/

Clone this repository:

```sh
git clone git@github.com:cgnd/docs.git
cd docs/
```

Create a Python virtual environment:

```sh
uv venv
```

Activate the virtual environment:

```sh
source .venv/bin/activate
```

Install Python dependencies:

```sh
uv pip install -r requirements.txt
uv pip install -r dev-requirements.txt
```

Run the builtin development server:

```sh
inv preview
```
