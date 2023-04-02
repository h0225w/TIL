# 코틀린 설치 방법 [MAC]

## 1. JDK 설치
```
# 설치 가능 버전 확인
brew search sdk

# 설치
brew install --cask [버전]

# cask 목록
brew list --cask

## Java 버전 확인
java -version
```

jdk 설치 시 ```--cask```를 사용하지 않으면 환경변수가 자동으로 설정되지 않음


## 2. Kotlin 설치
```
# 설치
brew install kotlin

# Kotlin 버전 확인
kotlin -version
```

## 3. VSCode 확장 프로그램 설치
1. Code Runner 설치
2. Kotlin Language 설치

## 4. 테스트
```kotlin
fun main() {
    print("Hello World!")
}
```

Code Runner 실행: Control + Option + N