# ubuntu
#### 1. 패키지 관리
- sudo apt-get update: 패키지 목록을 최신 상태로 업데이트합니다.
- sudo apt-get upgrade: 시스템에 설치된 패키지를 최신 버전으로 업그레이드합니다.
- sudo apt-get install [패키지명]: 패키지를 설치합니다.
- sudo apt-get remove [패키지명]: 패키지를 제거합니다.

#### 2. 파일 및 디렉토리 관리:
- ls: 현재 디렉토리의 파일 목록을 표시합니다.
- cd [디렉토리 경로]: 지정한 디렉토리로 이동합니다.
- cp [소스] [목적지]: 파일 또는 디렉토리를 복사합니다.
- mv [소스] [목적지]: 파일 또는 디렉토리를 이동하거나 이름을 변경합니다.
- rm [파일명]: 파일을 삭제합니다.
- mkdir [디렉토리명]: 새로운 디렉토리를 생성합니다.

#### 3. 권한 관리:
- chmod [권한] [파일명]: 파일의 권한을 변경합니다.
- chown [사용자명:그룹명] [파일명]: 파일의 소유자를 변경합니다.
- chgrp [그룹명] [파일명]: 파일의 그룹을 변경합니다.

#### 4. 프로세스 관리:
- ps: 현재 실행 중인 프로세스 목록을 표시합니다.
- top: 시스템의 실시간 프로세스 상태를 모니터링합니다.
- kill [프로세스ID]: 특정 프로세스를 종료합니다.

#### 5. 네트워크 관리:
- ifconfig 또는 ip addr: 네트워크 인터페이스의 정보를 표시합니다.
- ping [도메인 또는 IP 주소]: 지정한 호스트에 대한 네트워크 연결을 테스트합니다.
traceroute [도메인 또는 IP 주소]: 패킷이 네트워크를 통과하는 경로를 추적합니다.
시스템 정보 확인:

uname -a: 시스템의 커널 및 하드웨어 정보를 표시합니다.
lsb_release -a: 시스템의 Ubuntu 릴리스 정보를 표시합니다.
df -h: 디스크 사용량을 확인합니다.
