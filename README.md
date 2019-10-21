# Prerender Alpine

Lightweight Prerender container built on Alpine Linux with Node and Headless Chrome.

- Prerender 5.6.0
- Chromium 72.0.3626.121-r0
- Node 10.15.3

## Requirements

- Docker

## Usage

Pull and run the image:

```
docker pull temaowangluo/prerender
docker run -p 3000:3000 temaowangluo/prerender
```
Prerender will now be running on http://localhost:3000. Try the container out with curl:

```
curl http://localhost:3000/render?url=https://www.example.com/
```
