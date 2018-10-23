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

## Ref
* [依存関係管理ツールdep(golang)](https://qiita.com/Azizjan/items/66564b5dc7597717932b)
