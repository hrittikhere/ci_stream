[![Build Status](http://20.120.93.138/api/badges/hrittikhere/ci_stream/status.svg)](http://20.120.93.138/hrittikhere/ci_stream)

# ci_stream

```bash
    1  go mod init github.com/hrittikhere/ci-stream
    2  clear
    3  go mod tidy
    4  clear
    5  touch math_test.go
    6  clear
    7  touch .drone.yml
    8  go test
    9  git add .
```
