### 프로젝트 생성
예제로 아래 페이지를 따라하고 있음
https://medium.com/@minoo/react-typescript-ssr-code-splitting-%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0-d8cec9567871

#### 폴더구조
<pre>
프로젝트 폴더
 - dist
 - public
    * index_dev.html
 - src
    - components
      * Appbar.tsx
      * Footer.tsx
      * Header.tsx
    - pages
      * Home.tsx
      * Login.tsx
      * News.tsx
    * App.tsx
    * index.tsx
    * server.tsx
* babel.config.js
* package.json
* tsconfig.json
* wepack.config.js
* webpack.dev.js
* yarn.lock
</pre>


#### 구현 내용

1. Appbar 오른쪽 끝에 Login 버튼의 
2. 좌측에 아이콘 메뉴 추가
3. Window, Header, Body, Footer로 전체 페이지 구조적으로 정리