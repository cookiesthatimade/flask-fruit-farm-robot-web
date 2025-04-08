# 🍎 flask-fruit-farm-robot-web 🍎



> 자율주행 과수운반 로봇 웹

<img width="1205" alt="Image" src="https://github.com/user-attachments/assets/f65b2cbb-a612-42cf-8b0b-656abbf1ed9d" />

## 📖 프로젝트 소개

**flask-fruit-farm-robot-web**은 flask-fruit-farm-robot-web**은 과수원에서 작동하는 자율주행 운반 로봇(movebot)과 연동되는 웹 애플리케이션으로, 현재 로봇에 적재 된 과일의 종류, 적재량 등 적재정보와 실시간 날씨 등의 정보를 직관적으로 제공합니다.

### 🔹 주요 기능

1. **과일 적재 정보**
   - 적재된 과일의 상세 정보 제공
2. **로봇 안내 시스템**
   - 로봇 연동을 통해 현재 적재량과 남은 적재량 안내
3. **음성 인식**
   - 등록된 과일명 인식 시 적재량 및 상세 정보 제공
4. **자막 기능**
   - 화면에 로봇의 음성 안내 자막
4. **앱 설치(PWA)**
   - 브라우저를 통해 홈 화면에 앱 설치 가능
---

## 🎥 데모

<p align="left">
    <img src="https://github.com/user-attachments/assets/f65b2cbb-a612-42cf-8b0b-656abbf1ed9d" width="400" />
    <img src="https://github.com/user-attachments/assets/7a6461f4-682f-4d98-ad7c-a651cab122ca" width="400" />
    <img src="https://github.com/user-attachments/assets/b59ea728-cc8e-4361-afd0-18fbaba404d9" width="400" />
    <img src="https://github.com/user-attachments/assets/10363bab-e4d0-485d-9398-d9172f550f0f" width="400" />
    <img src="https://github.com/user-attachments/assets/24045b00-6f9f-42c3-8e5a-6f7e7fbb3d55" width="400" />
    <img src="https://github.com/user-attachments/assets/3e5ef23c-8e32-4bb4-9690-c8810ed6d064" width="400" />
</p>

---

## ⭐ 핵심 기술
### 🗄 데이터베이스 & 실시간 데이터 처리

- **MySQL** (pymysql 사용)
  - 테이블을 실시간 조회하여 적재 상태 관리

### 🎤 음성 인식 (STT) API 연동

- Google Speech-to-Text API 사용

### 🌍 웹 접근성 및 반응형 디자인 적용

- 다양한 디바이스에서 최적화된 UI 제공
- 버튼 클릭, 음성 입력 등의 인터랙션 지원
- 직관적 UI를 통한 간편한 사용

### 📱 PWA (Progressive Web App)
- 앱 설치 기능 지원
- 홈 화면에 바로가기 추가 가능
- 인터넷 연결이 불안정한 상황에서도 일부 기능 사용 가능 (Service Worker 기반)
 
---

## 💻 프로젝트 실행 방법

### 프로젝트 디렉터리 이동
```
cd app
```
### 가상 환경 생성
```
python3 -m venv env
```
### 가상 환경 활성화
```
source env/bin/activate
```
### 프로젝트 종속성 설치
```
pip install -r requirements.txt
```
### 서버 실행
```
python3 main.py
```
### ➡️ Go to localhost:5000

---

## 🔧 기술 스택

| **분류**            | **기술**                        |
| ----------------- | ----------------------------- |
| **언어**            | HTML, CSS, JavaScript, Python |
| **라이브러리 & 프레임워크** | Flask                         |
| **데이터베이스**        | MySQL                         |
| **배포 환경**         | AWS EC2, Docker               |
| **실행 환경**         | Gunicorn                      |
| **추가 기술**         | Google STT API, PWA (Service Worker, manifest.json) |


---

## 📁 프로젝트 구조

```markdown
src
├── app
│   ├── static
│   ├── templates
│   ├── main.py
│   └── my_settings.py (개별 작성 필요)
├── README.md
└── requirements.txt
```

---

## 👨‍💻 역할 및 기여

| 역할                 | 담당 업무                                                         |
| ------------------ | ------------------------------------------------------------- |
| **Frontend (Web)** | HTML, CSS, JavaScript (UI/UX 구현), PWA 설정                            |
| **Backend (Web)**  | Flask, MySQL                                         |
| **DevOps**         | AWS EC2, Docker, Gunicorn 배포 및 환경 설정                          |
| **Etc**             | 데이터베이스 운영, Google STT API 활용 |

---

## 👨‍👩‍👧‍👦 Developer
*  **김성하** ([cookiesthatimade](https://github.com/cookiesthatimade))
*  **김성욱** ([seonguk0893](https://github.com/seonguk0893))
