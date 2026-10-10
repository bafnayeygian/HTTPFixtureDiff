# HTTPFixtureDiff

Compare saved HTTP response fixtures and detect status, header, JSON body-shape, and contract drift between versions.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/HTTPFixtureDiff.git
cd HTTPFixtureDiff
python -m pip install .
```


Fixture JSON format can contain `status`, `headers`, and `body`.

```bash
http-fixture-diff old.json new.json
```


## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
