# AWSEBCLI exitcode issue

## Steps to reproduce

1. Clone this repo

1. Run `eb init`

1. Run `eb deploy`

## Result

```sh
$ eb deploy; echo ExitCode: $?
Creating application version archive "app-180330_131429".
ERROR: OSError - [Errno 2] No such file or directory: '<HOME>/go/src/test/vendor/git.apache.org/thrift.git/tutorial/erl/client.sh'
ExitCode: 0
```