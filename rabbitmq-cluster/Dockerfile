# haproxy/rabbitmq/Dockerfile
FROM rabbitmq:3.12.2-management

# 플러그인 설치 (내장 플러그인이므로 enable만)
RUN rabbitmq-plugins enable --offline rabbitmq_consistent_hash_exchange
