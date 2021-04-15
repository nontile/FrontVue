# Vue.js의 SSR 처리를 위한 Nuxt.js 프로젝트

## 개발환경구축

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:8080
$ npm run dev

# mock db
$ npm run db

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## 실행 스크립트 확인

package.json

## 환경설정파일

nuxt.config.js

.env.\*

## 기본개발가이드

1. 접속
   http://localhost:8080/guide

2. 좌측상단의 좌칙메뉴 열기 스위치 On

3. 필요한 component를 찾아서 사용한다.

4. 서버기본주소는 http://localhost:9110
   수정은 .env.\* 확인

5. 새로운 페이지 만들기
   pages 폴더에 폴더 생성후 index.vue를 작성하면 nuxt에서 auto routing 처리

   .nuxt/router.js 확인

| For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
