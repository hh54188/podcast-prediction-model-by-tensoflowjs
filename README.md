## How to run this training:

### If you are using NodeJS

1. Install http-server: 

```cmd
npm install http-server -g
```

2. Run `http-server` in this folder:

```cmd
http-server .
```

3. Access the local http server address in the browser. For example: `http://127.0.0.1:8000`

### If you are using Python

1. Run `http.server` in this folder:

```cmd
py -m http.server
```

2. Open the local http server address in the browser. For example: `http://127.0.0.1:8000`

## Caution

The model training page using [jsdelivr](https://www.jsdelivr.com/) as tfjs related libraries CDN provider. If you can not load the libraries, please try to switch to another CDN provider.