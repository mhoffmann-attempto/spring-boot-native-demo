# spring-boot-native-demo
A demo Application to test spring-boot-3 and spring native. This project was originally created with [Spring Initializr](https://start.spring.io/) 

## Preface
You need to install GraalVM with version __22.3+__. I use sdk man for managing VMs [sdkman](https://sdkman.io).

## Compile
`/gradlew nativeCompile`

# Run
## with gradle
`/gradlew nativeRun`

## as native Application
`./build/native/nativeCompile/demo`

## Links
- [sdkman](https://sdkman.io)
- [Spring Initializr](https://start.spring.io/)
- [Spring-Native Tutorial](https://docs.spring.io/spring-boot/docs/3.0.0/reference/html/native-image.html)