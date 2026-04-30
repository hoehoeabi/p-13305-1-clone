
## 1차 요구사항 구현
- [x] 유저가 루트 url로 접속시에 게시글 리스트 페이지(http://주소:포트/article/list)가 나온다.
- [x] 리스트 페이지에서는 등록 버튼이 있고 버튼을 누르면 http://주소:포트/article/create 경로로 이동하고 등록 폼이 나온다.
- [x] 게시글 등록을 하면 http://주소:포트/article/create로 POST 요청을 보내어 DB에 해당 내용을 저장한다.
- [x] 게시글 등록이 되면 해당 게시글 리스트 페이지로 리다이렉트 된다. 페이지 URL 은 http://주소:포트/article/list 이다.
- [x] 리스트 페이지에서 해당 게시글을 클릭하면 상세페이지로 이동한다. 해당 경로는 http://주소:포트/article/detail/{id} 가 된다.
- [x] 게시글 상세 페이지에는 id에 맞는 게시글 데이터와 목록 버튼이 있다. 목록 버튼을 누르면 게시글 리스트 페이지로 이동하게 된다.

- (추가 기능이나 구현기능설명이 필요한 경우 서술)

## 미비사항 or 막힌 부분
- ...

## UI/UX (화면 캡처본을 복사 붙여 넣기, url 주소 나오도록)
- 게시글 리스트 페이지

<img width="364" height="273" alt="스크린샷 2026-04-30 오후 6 07 12" src="https://github.com/user-attachments/assets/8b9e8ef9-5dbf-48b5-b89d-63f5ef28b38f" />
<img width="364" height="273" alt="스크린샷 2026-04-30 오후 6 08 08" src="https://github.com/user-attachments/assets/1ea80461-122d-4753-89dc-92a75aadedb3" />
- 게시글 등록 폼 페이지
<img width="364" height="273" alt="스크린샷 2026-04-30 오후 6 07 39" src="https://github.com/user-attachments/assets/e134148e-d74a-4af8-8caf-7831f9dbbb40" />
- 게시글 상세 페이지
<img width="364" height="273" alt="스크린샷 2026-04-30 오후 6 08 38" src="https://github.com/user-attachments/assets/eee6286b-a8ed-4c51-96d5-dfb7bb9702ac" />
- 게시물 수정 페이지
<img width="418" height="273" alt="스크린샷 2026-04-30 오후 6 09 55" src="https://github.com/user-attachments/assets/a4c7c3e5-979f-49e5-af24-9e3b8823b6d8" />
- 없는 게시물 조회 페이지
<img width="697" height="623" alt="스크린샷 2026-04-30 오후 6 10 43" src="https://github.com/user-attachments/assets/da89a046-22e2-4e69-b7ba-982bc382956c" />


## MVC 패턴
- ...

## 스프링에서 의존성 주입(DI) 방법 3가지 방법
- ...

## JPA의 장점과 단점
- ...

## HTTP GET 요청과 POST 요청의 차이
- ...
