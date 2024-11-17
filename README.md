# Go-CRUD-API-using-Gin-Framework
uz
* Hammaga Assalomu Alaykum, bu proyekt ochiq manba bo‘ladi) boshqa koderlarga yordam buladi) va savobham)

eng 
* Assalamu alaykum will be the open source project and help other coders and rewards.

ru
* Assalamu Alaykum будет проектом с открытым исходным кодом) и поможет другим кодеров) и вознаграждениям.


_________________
# autoUpdate: air
1. Plus tarafi: agar Windows/Mac/Linux Terminal autoUpdate air buladi va juda qulay.
2. Minus tarafi: agar siz **goLand** ishlatsangiz xar safar (CTRL + S) bosib zzz bulib ketasizlar xD

```bash
go install github.com/air-verse/air@latest
```

### Starting air
```bash
air
```
_________

## Testing the API for terminal
docs: https://www.codepedia.org/ama/how-to-test-a-rest-api-from-command-line-with-curl/
```bash
curl -I http://localhost:8000/api/healthChecker ## GET request
```

```bash
curl -i -X HEAD http://localhost:8000/api/healthChecker ## HEAD request
```

```bash
curl -X GET "http://localhost:8000/api/healthChecker" -H "accept: application/json" ## GET request
```

Agar siz uni yanada chiroyli ko'rsatishni istasangiz, `jq` tavsiya qilaman:
```bash
curl http://localhost:8000/api/healthChecker | jq . ## GET request
```

## Curl options
    -I or --head - fetch the headers only
    -i, --include - include the HTTP response headers in the output
    -X, --request - specify a custom request method to use when communicating with the HTTP server (GET, PUT, DELETE&)
