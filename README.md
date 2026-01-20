# RAG 챗봇 실습 환경 설정 가이드

RAG(Retrieval-Augmented Generation) 챗봇 실습을 위한 환경 설정 가이드 웹페이지입니다.

## 배포 URL

https://rag-setting-guide.vercel.app

## 프로젝트 구조

```
├── index.html          # 메인 가이드 페이지
└── images/
    ├── tip-cmd.png         # CMD 실행 팁 이미지
    └── tip-antigravity.png # Antigravity 실행 이미지
```

## 로컬 실행

```bash
python3 -m http.server 8000
```

브라우저에서 http://localhost:8000 접속

## 배포

Vercel CLI를 사용하여 배포:

```bash
vercel --prod
```
