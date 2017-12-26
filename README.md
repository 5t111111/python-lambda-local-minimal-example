# python-lambda-local Minimal Example

Create venv with Python3:

```
$ cd /path/to/python-lambda-local-minimal-example
$ python3 -m venv .
```

And activate it:

```
$ . bin/activate
```

Note that if you are using zsh/fish, source `acivate.zsh` / `activate.fish` instead.

Install requirements:


```
$ pip install -r requirements.txt
```

Run a Lambda function:

```
$ python-lambda-local -l lib/ -f handler -t 5 test.py event.json
```
