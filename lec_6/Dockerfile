# 이미지 베이스
FROM ubuntu

# 30초 간격으로 특정 사이트 접속 체크 
HEALTHCHECK --interval=30s --timeout=30s CMD [ "curl", "-f", "http://127.0.0.1", "||", "exit 1" ]
#DB체크 예시: HEALTHCHECK --interval=30s --timeout=30s CMD [ "musqladmin", "ping", "-h",  "http://127.0.0.1", "--password=1234", "--silent" ]