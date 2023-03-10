# howwatch
# 기능 정리

## 회원 )

### 로그인

- 판매 요청 목록
    - 판매 요청
- 판매목록 탐색
    - 카테고리 별로 보기
    - 판매 요청
- 구매
- 찜
- 장바구니

### 로그인 X

- 판매목록 탐색
    - 카테고리 별로 보기

## 관리자)

- 판매요청 목록 검토 → 판매목록
- 회원 관리
- 문의 사항 목록(보류)

## 판매 요청 흐름

회원 → 판매 요청 - 관리자 (검토) → 판매목록 등록

# 구현 해야할 것

## 이미지 가져오기

- spring boot로 부터 이미지 경로를 가져와서 react에다 보여주기

## DB 풀? (감이 안 잡힘)

- db풀을 왜 쓸까? 어떤 dependency를 써야 할까? hikariCP?

## 찜 눌렀을 때  DB로 비동기 처리? axios?

- 찜 버튼을 눌렀을 때 비동기 처리가 맞는 걸까? axios를 쓰는 방법은?

## 시계들을 db에 넣을 때 어떤 방식?

- 크롤링으로 이미지와 값들을 가져와서 넣어야 할 까?
    - 이게 안 되면 알 툴즈로 image들을 가져와서 넣어야 할 듯

## AWS로 클라우드에 서버를 띄우기

## Springboot와 react를 연동

## Springboot와 Mysql연결

## session을 react에서 어떻게 다루나?

## login → session? jwt?

- redux?

## 페이지 스타일은 어떤걸 써야 하나?

- bootstrap
- tailwind

# db 모델링
![SharedScreenshot2](https://user-images.githubusercontent.com/124124583/224296586-eb61bc1b-fddb-4150-a3a8-d29718b139de.jpg)

