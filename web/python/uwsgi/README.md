# Install
```
pip install uwsgi
```


# How to Use?

### make ini 
```
# path/to/project/uwsgi.ini

[uwsgi]
chdir = /home/sungju/projects/nomad/ocr_engine/src
uid = sungju
gid = sungju
chmod-socket = 666
socket = /tmp/uwsgi.sock
module = app:app
virtualenv = /home/sungju/projects/nomad/ocr_engine/envOCR
```


### run
```
uwsgi uwsgi.ini
```
