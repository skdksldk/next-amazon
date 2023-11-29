# Next-Amazon

## 프로젝트 설명
Next-Amazon은 이전에 제작했던 kakao를 기반으로 next.js와 typescript를 추가해서 만든 쇼핑몰입니다.
- nextjs를 통해 서버 사이드 렌더링을 공부하게 되었고 typescript를 지원할수 있게 되었음을 알게 되었습니다.
- typescript를 통해 에러를 사전에 알수 있으며 interface를 통해 상태관리 및 각 쇼핑물에 객체를 정의할수 있었으며 이를 통해 코드를 작성하는 시간을 줄었습니다. 
- stipe 결제 라이브러리를 통해 장바구니에 있는 쇼핑물들을 결제할수 있습니다.
- next-auth 라이브러리를 통해 Oauth Google login 기능을 첨부해 구글을 통한 로그인을 할수 있습니다.

### 🏃 구성원
- Frontend<br/>
  - 김준수(Next.js 13)
  - 사용 기술 : `Next.js 13`, `typescript`, `Redux`, `Stripe`, `Next-auth`, `Tailwind CSS`
 
## 🔎 기능 설명

### 1. 메인페이지
![1](https://github.com/skdksldk/next-amazon/assets/85090323/6950fa5a-7e31-428d-9ad2-ee9a407c7e2c)

![2](https://github.com/skdksldk/next-amazon/assets/85090323/b1149dd7-0230-4e69-9a88-b5d03e3292f9)

https://github.com/skdksldk/next-amazon/assets/85090323/ad39fe89-135c-40cd-959f-60e675428ea4

### 2. 로그인

![3](https://github.com/skdksldk/next-amazon/assets/85090323/c661d69f-fd3a-45b3-a9b2-754745652975)

- next-auth 라이브러리를 이용해 Oauth-Google login을 할수 있습니다.

### 3. 장바구니

![4](https://github.com/skdksldk/next-amazon/assets/85090323/861e2593-4f4c-4db7-99d5-2d674510ce21)

- Redux를 통해 상태관리로 메인 페이지의 add to cart 버튼으로 쇼핑물을 장바구니 페이지로 이동할수 있습니다.
- 로그인이 되어 있지 않은 경우 로그인을 해야 한다는 안내문이 뜹니다.

 ### 4. 결재

![5](https://github.com/skdksldk/next-amazon/assets/85090323/8117fd5e-b2c1-466b-8961-7a47ee4f64c5)

- Stripe 라이브러리로 장바구니에 있는 쇼핑물을 결재 할 수있습니다. 결재가 왼료된후 go to shopping 안내문이 뜨면서 초기회됩니다.


## 💻 배포 링크

[Amazon](https://next-amazon-lyart.vercel.app/)

## 💻 출처 자료

[Redux](https://velog.io/@skdksldk2/Redux%EB%A1%9C-%EC%83%81%ED%83%9C%EA%B4%80%EB%A6%AC-%ED%95%98%EA%B8%B0) <br/>
[Typescript](https://velog.io/@skdksldk2/%ED%83%80%EC%9E%85%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8) <br/>
[Next-Auth](https://velog.io/@skdksldk2/Next-Auth) <br/>
[Stripe](https://velog.io/@skdksldk2/Stripe)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
