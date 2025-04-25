# gowithmods
Sample Go application using modules

## Usage
1. Start the app:
```
cd emoserv
go run .
```
2. Run a search:
```
curl -d '{"include":["fruit"]}' http://127.0.0.1:8080/search
```