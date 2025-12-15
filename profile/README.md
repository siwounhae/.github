## 시워언해(Siwounhae)

🧖 찜질방 예약/정보 제공 및 ai 추천 기능을 포함한 플랫폼입니다.

<br>

## Overview

### Project Management
- **Docs**: https://www.notion.so/siwounhae-2a8e2e29c8d2801b9df1e38c4432b20d
  
  프로젝트 일정, 계획, 이슈 및 트러블 슈팅 등 작업 흐름을 정리한 문서

---

### Architecture
- **ERD**: https://www.erdcloud.com/d/mMLtWjSgsQishJJfw
  
  시워언해 도메인 별 핵심 데이터 모델 구조

---

### DevOps
- **infra-config**
  
  Nginx 및 Docker Compose 기반 인프라 설정, dev/prod 환경별 구성 파일을 분리하여 관리

---  

### Server
- **account-service**
  
  사용자 계정, 프로필, 인증·인가(Auth) 관련 기능을 담당하는 서버

- **spa-service**
  
  찜질방 도메인 서비스로, 리뷰 및 관련 비즈니스 로직을 처리

- **common-lib**
  
  서버 전반에서 공통으로 사용하는 유틸, 에러, 타입, 헬퍼 라이브러리

---

### Client
- **app-mobile**
  
  React Native 기반의 크로스 플랫폼 모바일 애플리케이션

---

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
