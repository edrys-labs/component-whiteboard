# Edrys Whiteboard Component

This module adds a live whiteboard to Edrys (every room has its own whiteboard). It is based on [Excalidraw](https://excalidraw.com).
 
## Usage

Simply add this URL to your class modules:

```
https://edrys-labs.github.io/module-whiteboard/
```

## Development

Please note **this module will only work when your Edrys server is running behind HTTPS**. Otherwise you will get errors about decryption failing. You can use [Caddy](https://caddyserver.com/download) to easily acheive that, for example:

```
caddy reverse-proxy --from localhost:8001 --to localhost:8000
```

This will run a new HTTPS server on https://localhost:8001 (assuming your Edrys is running at http://localhost:8000).
