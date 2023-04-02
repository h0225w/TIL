# Go 설치 방법 [MAC]

## 1. Go 설치
https://go.dev/dl/ 이동 후 맥 OS용 파일 다운로드

```
# Go 버전 확인
go version
```

## 2. VSCode 확장 프로그램 설치
- Go 설치

## 3. 테스트
```go
// hello.go
package main

import "fmt"

func main() {
    fmt.Println("Hello World!")
}
```

```
# Go 모듈 생성
go mod init goproject\hello

# Go 실행 파일 생성
go build

# 실행 파일 실행
./hello
```

