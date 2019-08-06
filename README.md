# Gin Heroku demo

## heroku

* heroku dashboard https://dashboard.heroku.com/apps/gin-demo/
* app https://gin-demo.herokuapp.com/

## local test

```bash
go mod vendor
go build -o gindemo
PORT=5000 ./gindemo
# goto localhost:5000
```