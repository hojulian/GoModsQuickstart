# GoModsQuickstart

*For those who are as forgetful as I am...*

To use Go mod inside of gopath
```
export GO111MODULE=on
```

To initialize Go mod
```
go mod init
```

To add dependencies to go.mod
```
go get -u ./...
```

To create vendor folder with dependencies
```
go mod vendor
```

To update a dependency
```
go get -u https://github.com/link/to/repo
```
