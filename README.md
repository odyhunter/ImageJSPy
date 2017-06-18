# ImageJSPy

## To run need following, flask as main server, Pillow is lib for picture convert
```
pip install flask
pip install Pillow
```

## For handle large number of concurrent uploads
1) A pytest concurrent module to test what the issue will be look like in case of large concurrent uploads (Login & Session will be needed) 
2) Embeded Flask webserver should not be used in production. Gunicorn + Nginx can be employed



