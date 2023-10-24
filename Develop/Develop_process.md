# 개발 프로세스 작성하기

## 개발 주간 업데이트 작성하기

> 이번주 목표 

>> 세분화된 목표

>> 추상화

>> 테스트 목표

## 예제 만들기


> 목표
- 비디어 편집 툴 만들기
- SensPet 측정 디자인 바꾸기 

> 세분화된 목표
- 영상 재생 구간
    - 영상 소스 입력
    - 영상 실행 / 정지 
    - 전체 실행시간

- 영상 편집 구간 (라이브러리 카피하기)
    - 편집될 실행시간
    - 구간내 자동 시작, 반복

> 추상화

~~~
<비디오 편집>
	- 편집된 시작 시간, 끝시간
	- 영상 편집툴
	- 영상 길이 편집
	- 영상 저장

<비디오 Util>
	- 비디오 재생시간
	- 비디오 제목
	- 비디오 Uri
	
<비디오 플레이어 관리>
	- Player
	- 플레이어 재생 Uri Setting
	- 플레이어 재생 구간 설정
 	- 플레이어 옵션 설정
	- 플레이어 시작
	- 플레이어 정지
	- 플레이어 이동
~~~

> 테스트 목표

(1) 비디오 플레이 관리
- [ ] 비디오 자동시작
- [ ] 비디오 반복 재생
- [ ] 비디오 플레이 선택 구간별 재생하기

(2) 비디오 힌트뷰
- [ ] 전체 재생 길이
- [ ] 구간 편집 길이
	
(3) 비디오 편집
- [ ] 비디오 구간 편집 저장

(4) 디바이스 연계
- [ ] 생명주기에 따른 실헹 / 정지 관리 


## 회고
