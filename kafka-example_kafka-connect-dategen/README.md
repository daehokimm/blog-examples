# Kafka Example - kafka-connect-datagen

kafka-connect-datagen 환경 구성을 위한 예제 코드입니다.
`.env` 파일에 원하는 버전을 입력한 뒤 `docker-compose` 명령어를 통해 환경을 구성합니다.

```sh
docker-compose up -d
```

구성되는 컨테이너는 다음과 같습니다.

- zookeeper : 카프카 구성을 위한 주키퍼
- broker : 카프카 브로커
- connect : 카프카 커넥트
