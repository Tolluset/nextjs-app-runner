# AWS App Runner에 Nextjs 배포해보기

아래의 블로그에서 사용하는 코드입니다.

[https://dev.classmethod.jp/articles/next-js-aws-app-runner/](https://dev.classmethod.jp/articles/next-js-aws-app-runner/)


## Getting Started

```bash
docker build -t nextjs-app-runner .
docker run -p 3000:3000 nextjs-app-runner
```
