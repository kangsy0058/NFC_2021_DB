# DB 폴더 설명
 
## DB-compose
 
* mariaDB 와 redis 를 한번에 세팅
* docker 와 docker-compose 가 설치되어있는환경에서 docker-compose up -d 명령어로 사용
* maria-init-files 안에 sql파일을 변경하면 변경된 sql문으로 실행됨
* 기본적으로 설정되는 root계정 비밀번호는 docker-compose.yml 파일안'MYSQL_ROOT_PASSWORD'에 설정되어있음
* redis 비밀번호는 redis-init-filse안에 redis.conf 파일안에 저장되어있음

## sql-files

* sql 스크립트들을 저장해둔 폴더