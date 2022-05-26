# scf-nginx-container-image-demo
Demo for nginx container image

## SCF Configuration

```bash
镜像	xxx.tencentcloudcr.com/chris_demo/scf_nginx:1.0
镜像URL	xxx.tencentcloudcr.com/chris_demo/scf_nginx@sha256:ee48d89f4812880a7ddc216a53ec0297c59cd0ab6bc756533f222221cf2d4d52
ENTRYPOINT	
CMD
```

## Test

- check the URL for APIGateway trigger, eg. https://service-xxxx.gz.apigw.tencentcs.com/release/
- curl https://service-xxxx.gz.apigw.tencentcs.com/release/

```html
<!DOCTYPE html>
<html>
<head>
<title>Welcome to nginx!</title>
<style>
html { color-scheme: light dark; }
body { width: 35em; margin: 0 auto;
font-family: Tahoma, Verdana, Arial, sans-serif; }
</style>
</head>
<body>
<h1>Welcome to nginx!</h1>
<p>If you see this page, the nginx web server is successfully installed and
working. Further configuration is required.</p>

<p>For online documentation and support please refer to
<a href="http://nginx.org/">nginx.org</a>.<br/>
Commercial support is available at
<a href="http://nginx.com/">nginx.com</a>.</p>

<p><em>Thank you for using nginx.</em></p>
</body>
</html>
```
