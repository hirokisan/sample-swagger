# sample-swagger

## Validate
```
$ swagger validate ./swagger.yml
```

## Generate server
```
$ swagger generate server -A todo-list -f ./swagger.yml
```

## Install dependency packages
```
$ dep ensure
```

## Generate executable file
Executable file will be generated at $GOPATH/bin

```
$ go install ./cmd/todo-list-server/
```

## Run
```
$ todo-list-server
```

## Notice
Files below is safe to edit

```
restapi/configure_todo_list.go
```

## Ref
* [Swagger Tutorial](https://goswagger.io/tutorial/todo-list.html)
* [依存関係管理ツールdep(golang)](https://qiita.com/Azizjan/items/66564b5dc7597717932b)
