# How to use CSP:
### Using meta tag:
```
<meta http-equiv="Content-Security-Policy"content="default-src 'self'; img-src https://*; child-src 'none';" />

<meta http-equiv="Content-Security-Policy"content="default-src * data:; style-src 'self' 'unsafe-inline'; img-src 'self' data:; script-src 'self' 'unsafe-inline' 'unsafe-eval'; https://yourdomain.com" />
```
