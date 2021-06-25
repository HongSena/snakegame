# SnakeGame

2021년 1학기 C++프로그래밍 프로젝트로 진행된 ncurses를 이용한 SnakeGame Project입니다.

| 이름          | 학번     |
| ------------- | -------- |
| 김민정 (팀장) | 20191556 |
| 김은수        | 20191568 |

# 컴파일&실행방법
1. snakegame 디렉토리 안에 진입해서 다음과 같은 Command line 명령어를 통해 Build 환경을 구축
cmake -DCMAKE_CXX_COMPILER=g++ -DCMAKE_CXX_STANDARD=14 -DCMAKE_VERBOSE_MAKEFILE=ON -DCMAKE_BUILD_TYPE=Release -GNinja .

2. Package를 Ninja를 통해 Linking
ninja

3. 생성된 실행 파일을 다음과 같은 명령어를 통해 실행
./snakegame
