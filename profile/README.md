[![horizontal_logo_light_theme](/image/horizontal_logo_light_theme.svg)](https://try-catch.kr)


# 트라이캐치(Try-Catch)
## 소개
### "개발자를 위한 커뮤니티"
>개발자를 위한 커뮤니티
>한국판 Stack Overflow
>GitHub 정보를 바탕으로 기술 블로그 글 추천

<br>

## **📚 목차**  

1️⃣ [타겟층](#-타겟층)   
2️⃣ [주요 기능](#-주요-기능)  
3️⃣ [트라이캐치 서비스](#-트라이캐치-서비스)  
4️⃣ [실행방법](#-실행방법)  
5️⃣ [팀 구성](#-팀-구성)  
6️⃣ [기술 아키텍쳐](#-기술-아키텍쳐)  
7️⃣ [ERD 다이어그램](#-erd-다이어그램)  
8️⃣ [API 명세서](#-api-명세서)   
🔟 [협업 툴](#-협업-툴)  
☑ [향후 계획](#-향후-계획)

<br>

## 😮 타겟층
    ✔ 언어장벽에 부딪힌 개발자
    ✔ 자신의 지식을 나누고 싶은 개발자
    ✔ 기업 기술블로그를 한눈에 보고싶은 개발자
    
    추후) 홍보를 원하는 개발자나 기업
    
<br>

## 👍 주요 기능(아직 미완성)
|구분|기능|설명|비고|
|:---|:---|:---|:---|
|1|사용자|회원가입, 로그인이(깃허브) 가능하다.<br>알림을 확인할 수 있다.<br>다크모드 설정이 가능하다.<br>회원 정보를 수정할 수 있다.<br>||
|2|Q&A 서비스|사용자가 질문 및 답변을 작성할 수 있다.<br>마음에 드는 답변을 채택할 수 있다.<br>질문 즐겨찾기가 가능하다.<br>질문과 답변에 좋아요가 가능하다<br>실시간 인기 태그 및 인기 질문을 추천해준다.<br>태그와 키워드 검색이 가능하다.||
|3|기술블로그 피드|피드를 두 가지(카드, 리스트)뷰로 볼 수 있다.<br>구독한 블로그만 필터링 해서 볼 수 있다.||<br>||
|4|로드맵|피드를 두 가지(카드, 리스트)뷰로 볼 수 있다.<br>구독한 블로그만 필터링 해서 볼 수 있다.||
|5|챌린지|피드를 두 가지(카드, 리스트)뷰로 볼 수 있다.<br>구독한 블로그만 필터링 해서 볼 수 있다.||
|6|개인화|피드를 두 가지(카드, 리스트)뷰로 볼 수 있다.<br>구독한 블로그만 필터링 해서 볼 수 있다.||

<br>

# 🌍 트라이캐치 서비스
## 📌 Q&A
- 질문 생성
  - 수정 및 삭제
  - 노션처럼 사용
  - 댓글 생성
  - 댓글 채택
  - 좋아요, 즐겨찾기
  - 무한스크롤
![qna-post](https://user-images.githubusercontent.com/77381154/219595260-4adfe12a-4e0e-49cc-a069-f143aa021883.gif)

- 답변 생성 시 깃허브 자동 커밋
# !!! 내일 백엔드에 요청해서 디비 지워달라고 하기
![커밋 과정 GIF]()


---

## 📌 피드
- 피드 페이지
  - 구독
  - 카드, 리스트 뷰 전환
  - 무한스크롤
  - 개인화(깃허브 리포지토리 기반)
![feed](https://user-images.githubusercontent.com/77381154/219680052-1b8e8f11-b1d8-4c71-a319-ac5a011ec390.gif)

- 피드 고급검색
  - [lucene-query](https://www.lucenetutorial.com/lucene-query-syntax.html)를 활용한 검색
![feed-search](https://user-images.githubusercontent.com/77381154/219682694-85a09293-60a1-4df8-93e1-8baa8c89e2f2.gif)

---

## 📌 로드맵
- 공통 로드맵
![Roadmap](https://i.imgur.com/bu2aZs3.png)

- 커스텀 로드맵 생성
![create-roadmap](https://user-images.githubusercontent.com/77381154/219678448-e9bcbdb2-79b1-4bbf-b215-57190d05ce9b.gif)

---

## 📌 챌린지
- 커뮤니티 활성화 역할
![challenge](https://user-images.githubusercontent.com/77381154/219686429-00271d92-7afb-40fd-9a6d-b6cf3a0cbc8b.gif)


---


## 📌 유저 페이지
- 팔로우, 팔로잉, 구독 관리
- 최근 본 피드, 작성한 질문, 댓글 리스트
- 획득한 뱃지 리스트
![user](https://user-images.githubusercontent.com/77381154/219690029-b8db7f6e-fb80-4e40-9b36-446b479095d2.gif)

---

## 📌 다크 모드
- 모든 페이지 다크 모드 구현
![darkmode](https://user-images.githubusercontent.com/77381154/219684362-29a19bc9-32c8-417a-8ba5-b15dad754ac8.gif)


---

## 📌 즐겨찾기
- Q&A, 북마크, 로드맵 즐겨찾기
![bookmark](https://user-images.githubusercontent.com/77381154/219683810-b282e870-3763-4cba-8280-70c70828c591.gif)


<br>


## 시스템?

<br>

## 👬 팀 구성
<table>
  <tr>
   <td align="center">
   <p>OPS</p>
   <a href="https://github.com/Bogyie"><img src="https://avatars.githubusercontent.com/Bogyie" width="100px;" alt=""/>
       <br />
           <sub>
                <b>Bogyie</b>
                <br>
           </sub>
       </a>
   </td>
   <td align="center"><p>FE Leader</p><a href="https://github.com/ChangJuneKim"><img src="https://avatars.githubusercontent.com/ChangJuneKim" width="100px;" alt=""/>
   <br /><sub><b>ChangJuneKim</b><br></sub></a></td>
   <td align="center"><p>FE</p><a href="https://github.com/hyeonaseome"><img src="https://avatars.githubusercontent.com/hyeonaseome" width="100px;" alt=""/>
   <br /><sub><b>hyeonaseome</b><br></sub></a></td>
   <td align="center"><p>FE</p><a href="https://github.com/nimusmix"><img src="https://avatars.githubusercontent.com/nimusmix" width="100px;" alt=""/>
   <br /><sub><b>nimusmix</b><br></sub></a></td>
   <td align="center"><p>BE Leader</p><a href="https://github.com/hyeok00"><img src="https://avatars.githubusercontent.com/hyeok00" width="100px;" alt=""/>
   <br /><sub><b>hyeok00</b><br></sub></a></td>
   <td align="center"><p>BE</p><a href="https://github.com/EZ-000"><img src="https://avatars.githubusercontent.com/EZ-000" width="100px;" alt=""/>
   <br /><sub><b>EZ-000</b><br></sub></a></td>
   
  </tr>
</table>


 

## 💾 실행방법
- **Frontend**
```
npm install
npm run dev
```

- **Backend**
```
백엔드 실행방법
```



<br>

## 👨‍💻 기술 아키텍쳐
![image](https://user-images.githubusercontent.com/77381154/219697411-554acb14-b6ff-4080-a4c7-31e8d9429dbc.png)


<br>

## 💎 ERD 다이어그램
![TRY_CATCH_DB](https://user-images.githubusercontent.com/77381154/219697030-a51896dd-3855-4792-9323-dd42dd23c492.png)


<br>

## 📘 API 명세서
### [API 명세서](https://right-longship-995.notion.site/Try-Catch-API-87f9468fa4cc4fa6b1ad72a48748ee03)
![image](https://user-images.githubusercontent.com/77381154/219701809-2f8a1c76-95e3-4291-af0b-630a82fd24c3.png)


<br>

## 🍏[와이어프레임](https://www.figma.com/file/uPdX36WzxiC6ecnBGcTGiy/trycatch?node-id=0%3A1&t=JWlLFyMJgh7ts03r-1)
![image](https://user-images.githubusercontent.com/77381154/219699671-d29c9b24-9f2c-46ba-8e2b-802ffa712cd7.png)



<br>

## 👊 협업 툴
- [노션](https://www.notion.so/boggy/42-ab06787c38ea4f349cf638a3209cb571)
- [피그마](https://www.figma.com/file/uPdX36WzxiC6ecnBGcTGiy/trycatch?node-id=0%3A1&t=JWlLFyMJgh7ts03r-1)
- 지라
- 디스코드
- 매터모스트
- 깃랩, 깃허브
- SpotLight

<br>

## ✅ 향후 계획
- 유지보수
- 챌린지 깃허브 연동
- 피드 구독 뉴스레터(메일링 서비스)
    
<br>

## ⭐ 수상 내역(아직 없음)

    🏆 삼성 청년 SW 아카데미(SSAFY) 공통 프로젝트 우수 상 하나 주라

상장 이미지
