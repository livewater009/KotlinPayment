## Usage
```kotlin
val config = Paymongo.Config.apply{
   secretKey = "sk_123456"
}
val client = PayMongo(config)
```
## Ktor Webhook Integration
https://github.com/ronjunevaldoz/KotlinPaymongo/wiki/Ktor-Webhook

## Installation
```kotlin
repositories {
   mavenCentral()
}
```

## Common Dependency
```kotlin
implementation("io.github.ronjunevaldoz:paymongo-kotlin:<VERSION>")
```
## Platform specific dependency (jvm, ios, android, wasmjs)
```kotlin
implementation("io.github.ronjunevaldoz:paymongo-kotlin-<PLATFORM>:<VERSION>")
```