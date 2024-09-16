Docker Compose 정리 및 예제입니다.

# 자주 사용하는 Docker Compose CLI

# compose.yml 파일을 기반으로 컨테이너들을 실행
$ docker compose up

# -d : 백그라운드 실행(기본 포어그라운드)
$ docker compose up -d

# --build : compose.yml 에 정의된 모든 서비스의 이미지를 새로 빌드
$ docker compose up --build

# compose.yml 에 정의된 이미지들을 다운로드하거나 갱신
$ docker compose pull

# compose 로 실행한 컨테이너들만 조회
$ docker compose ps

# -a : 실행 중인 컨테이너와 실행 중이지 않은 컨테이너를 모두 조회(기본 실행 중인 컨테이너만)
$ docker compose ps -a

# compose 로 실행한 컨테이너들의 로그만 조회
$ docker compose logs

# compose 로 실행한 컨테이너들을 종료
$ docker compose down
