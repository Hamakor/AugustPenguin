Website for August Penguin 2018  http://ap.hamakor.org.il

## Suggesting Changes

### Using GitHub Web UI

* Click "Edit" on the relevant html file you want to modify
* GitHub will allow you to edit it and will create a pull request for you (so we can decide if to accept / decline or modify your changes)

### Using Standard Git flow

* Fork and clone the repo (it should automatically use the latest branch - ap2018)
* edit the files locally
* You can open the local html files directly in a browser, or you can use Python's built-in http module (or any other way to serve files):
```
~/AugustPenguin$ python -m SimpleHTTPServer
Serving HTTP on 0.0.0.0 port 8000 ...
```
* Site should be available at http://localhost:8000
* Commit and push your changes to your fork
* Open a pull request
