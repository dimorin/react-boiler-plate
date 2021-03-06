# react boiler plate
## 소개
서버(mongoDB) 와 클라이언트(react) boiler plate 만들기<br>
- 랜딩페이지, 로그인 페이지, 회원가입 페이지
- 로그인, 로그아웃 기능
- 로그인 여부에 따라 페이지 컴포넌트 달라짐(HOC)
<br>
[원본 유튜브 강의](https://www.youtube.com/watch?v=fgoMqmNKE18&list=PL9a7QRYt5fqkZC9jc7jntD1WuAogjo_9T)
<br>
[원본 github](https://github.com/jaewonhimnae/boiler-plate-ko)

## 실행방법
```bash
npm i

# client 와 server 동시에 실행
npm run dev
```

## CORS 이슈, Proxy 설정
해결방법
[https://create-react-app.dev/docs/proxying-api-requests-in-development#configuring-the-proxy-manually](https://create-react-app.dev/docs/proxying-api-requests-in-development#configuring-the-proxy-manually)

## css framework
[https://ant.design/](https://ant.design/)

## form
로그인과 회원가입을 Formik 과 Yup 라이브러리로 좀더 다이나믹하게 만들 수 있다.
<br>
[https://formik.org/](https://formik.org/)
<br>
[Yup](https://www.npmjs.com/package/yup)

## HOC
고차 컴포넌트(HOC, Higher Order Component)<br>
고차 컴포넌트는 컴포넌트를 가져와 새 컴포넌트를 반환하는 함수입니다.
[https://ko.reactjs.org/docs/higher-order-components.html](https://ko.reactjs.org/docs/higher-order-components.html)