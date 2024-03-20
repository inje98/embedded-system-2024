# embedded-system-2024
IoT 개발자 임베디드 시스템 학습 리포지토리


## 1일차

- 라즈베리파이 설치 및 개발환경 세팅
	- Putty
	- Rasberry Pi Imager
	- Sd Card Formatter
	
- 순서
	 1. sd카드 포맷 (Sd Card Formatter)
	 2. Rasberry Pi Imager에서 설정하기
	 3. Putty에서 공유기 연결하고 open
	
## 2일차

- 기본 명령어
	- sudo -> 관리자권한
	- sudo apt update
	- sudo apt upgrade -y

	- clear         : 화면 클리어
	- ls            : 현재위치 파일 확인
	- pwd 		    : 현재위치
	- mkdir 파일명  : 파일 생성
	- rm -fr 파일명 : 파일 삭제
	- cd 파일명     : 파일 들어가기
	- cd ..         : 부모파일 들어가기
	
## 3일차
- 기본 명령어

	- 리눅스 명령어 (https://m.hanbit.co.kr/channel/category/category_view.html?cms_code=CMS6390061632)

	- nanorc => nano /etc/nanorc
	- gcc -o test01 test01.c => ./test01
	- gcc test01.c => ./a.out
	- enum(열거형)
	- func(함수 정의 -> 함수 호출)
	- 함수 선언 -> 함수 호출 -> 함수 정의
	- input 선언
	
## 4일차
	
- 자료구조
		- 연결리스트
		
## 5일차

- 자료구조
	- 스택(Last in First Out)
	- 큐(First in First Out)
	
## 6일차

- 자료구조
	- 연결리스트로 큐 구현
	
- makefile만들기
	1. nano makefile
	2. 별명: 파일명.o
           gcc -o 별명 파일명.o
	   파일명.o: 파일명.c
           gcc -c 파일명.c
    3. make
	4. ./별명

## 7일차

- 자료구조
	- 정렬(버블정렬)
	- 이진탐색트리
	
- 파일 입출력
	- 교재 p.30, 32 예제