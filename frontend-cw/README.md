# Frontend for Cloudflare Worker CRUD App
## Setup Instructions
1.
```
git clone https://github.com/Korrawit-aoongern/frontend-cw
```

2.
```
cd frontend-cw
```

3.
```
docker pull yuzuruorensu/cw-crud:v1f
```

4.
```
docker run -p 8080:80 -e API_BASE=https://<your-cloudflare-worker-url-api>.dev yuzuruorensu/cw-crud:v1f
```

5.
```
https://localhost:8080
```

