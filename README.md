# 🐺 WebWolf Clone - 보안 실습용 공격 시뮬레이션 서버

이 프로젝트는 **웹 보안 교육 및 실습**을 위한 가벼운 Express.js 기반의 WebWolf 클론입니다.  
PortSwigger Web Security Academy, OWASP WebGoat, DVWA 등에서 요구하는 **외부 서버 상호작용 문제 (CSRF, XSS, SSRF, Blind XSS 등)**를 해결할 수 있도록 설계되었습니다.

---

## 📌 주요 기능

| 기능 유형         | 설명 |
|------------------|------|
| 🔐 CSRF 시뮬레이션  | 자동 요청을 수신하고 로그 기록 |
| 🎯 XSS 수신       | `document.cookie`, 토큰 등 탈취된 정보 수신 |
| 🧪 Blind XSS 테스트 | 브라우저 기반 피드백 없는 요청 수신 |
| 📬 커스텀 공격 HTML 서빙 | 공격용 페이지 정적 파일로 제공 가능 |

---

## 🛠️ 실행 방법

### 1. 설치

```bash
git clone https://github.com/yourname/webwolf-clone.git
cd webwolf-clone
npm install
