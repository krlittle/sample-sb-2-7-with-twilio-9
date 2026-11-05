# sample-sb-2-7-with-twilio-9

Sends a text message over REST.

## Stack

- Spring Boot 2.7.18
- Java 17
- Gradle 8.4
- Twilio 9.14.1

## Build

```
./gradlew build
```

## Run

```
./gradlew bootRun
```

Set `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN` and `TWILIO_FROM_NUMBER` first.

```
curl -X POST localhost:8080/texts -d to=+15550002222 -d body=hello
```
