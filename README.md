A simple UI for [etcd](https://github.com/coreos/etcd)

## Running without Vagrant

First start etcd with CORS enabled for globally:

```
etcd -cors='*'
```

Then start a simple server at the base of the wetcd directory.

```
cd public
python -m SimpleHTTPServer 8000
open http://127.0.0.1:8000
```
