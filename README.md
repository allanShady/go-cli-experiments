# go-cli-experiments

### setup
* setup $ROOT and $GOPATH environment variables
```shell
    export GOPATH=$HOME/go
    export GOBIN=$GOPATH/bin
    export PATH=${PATH}:$GOBIN:$GOROOT/bin
```
* init cli module `go mod init github.com/allanShady/go-cli-experiments`
* Install cobra `go get -u github.com/spf13/cobra/cobra` to **bin** path
* get viper `go get github.com/spf13/viper@v1.8.1`
* add get `cobra add get`
* using task file:
    * `task build`
    * `task run`
    * `task clean` 
