# chalice-simple
Simple Chalice

```
$ python3 --version
Python 3.7.3
$ python3 -m venv venv
$ . venv/bin/activate
$ python3 -m pip install chalice httpie

$ chalice --help
Usage: chalice [OPTIONS] COMMAND [ARGS]...

$ chalice local
$ chalice deploy [PROFILE]
$ chalice delete [PROFILE]
```


```
$ http <URI>
$ http <URI>/hello/{name}
$ echo '{"user":"viuda"}' | http POST <URI>/users 
```


