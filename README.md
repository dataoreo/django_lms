# 🎓 Django Learning Management System

### **"Django 기반 온라인 학습관리시스템(Learning Management System)"**


📅 **Development Period** : 2025.09 ~ 2025.12 (3달)

</div>

---

# 📌 프로젝트 개요

Django를 활용하여 개발한 **Learning Management System(LMS)** 입니다.

* 배경 : 본 프로젝트는 데이터베이스 전공 수업의 팀 프로젝트로 진행되었습니다. DORO의 요구사항을 바탕으로 온라인 학습관리시스템(LMS)을 설계하고 구현하며, 데이터베이스 설계와 웹 애플리케이션 개발 과정을 경험하는 것을 목표로 했습니다.

---

# 👨‍💻 팀 구성

* 이성재(팀장) : UI/UX 디자인
* 김형준 : 프론트엔드
* 윤세훈 : 프론트엔드
* 권오준 : 로그인/회원가입/비밀번호 재설정 기능 개발, 강의실 및 공통 기능 개발
* 김민규 : 게시판 기능 개발, ERD 설계, DB 모델 설계 및 초기 구축
* 홍정표 : FAQ 기능 개발

---

# ✨ 주요 기능

### 👤 User

* 회원가입 중복확인
  <img width="900" height="400" alt="중복확인" src="https://github.com/user-attachments/assets/fe1fd4f1-639c-4bae-a44d-80d78e6a4099" />


* 이메일 인증
  <img width="600" height="500" alt="회원가입 및 이메일 인증" src="https://github.com/user-attachments/assets/41aa01a5-da7a-4d38-bc2c-b8423c9d5313" />

* 아이디 비밀번호 찾기
  <img width="577" height="501" alt="아이디 찾기" src="https://github.com/user-attachments/assets/c29195d9-68c9-47e1-8a85-4d69f9d47223" />
  <img width="757" height="614" alt="비밀번호 재설정 및 로그인" src="https://github.com/user-attachments/assets/2d2bdad3-e55b-4876-8bcc-04585e16e6fd" />

<br>

### 📚 Course

* 강의 생성 및 조회
  <img width="1300" height="634" alt="강의 등록" src="https://github.com/user-attachments/assets/55351d27-993d-4d6e-9d60-e183519b49e0" />

* 강의 신청
  <img width="1338" height="652" alt="강의신청" src="https://github.com/user-attachments/assets/fd6a9294-33dd-4b91-bc6d-8052c8f65407" />
  <img width="372" height="92" alt="image" src="https://github.com/user-attachments/assets/d271b121-f728-45b3-a918-b522cc2899a2" /> 중복 일정일 경우 강의 신청이 불가능합니다.

* 학습 자료 업로드
  <img width="1338" height="652" alt="자료 관리" src="https://github.com/user-attachments/assets/526d2adc-d412-4c55-a86c-936529be2a54" />

* 강의 질문 게시판
  <img width="1338" height="652" alt="강의실 질문 게시판" src="https://github.com/user-attachments/assets/8fb8c4b1-bc10-41e5-b8f1-049d3eb2726d" />

* 과제 제출 및 피드백
  <img width="1338" height="652" alt="과제 제출 및 피드백" src="https://github.com/user-attachments/assets/dd660671-8a0a-4bcb-ac6b-9d70c7500645" />

### 📝 Board

* 공지사항
  <img width="1338" height="652" alt="공지사항" src="https://github.com/user-attachments/assets/1858d612-1f03-46b3-9e81-145f5a3bf89a" />

* 게시글 작성
  <img width="1338" height="652" alt="게시판" src="https://github.com/user-attachments/assets/14edd6f9-7709-4e22-8f9c-cb58f4f29ac8" />

* 게시글 수정 및 삭제
 <img width="1338" height="652" alt="게시글 수정 삭제" src="https://github.com/user-attachments/assets/c7f50e8f-6a46-4491-8bca-553f085d5ffa" />
  
* 댓글 기능
  <img width="1338" height="652" alt="댓글" src="https://github.com/user-attachments/assets/c0cf5785-ce73-4ca6-9625-7b8fc9a768ce" />
  댓글 삭제 로직 : 대댓글이 달린 본댓글이 삭제될 시 "삭제된 댓글입니다." 표시, 대댓글도 삭제될 시 완전 삭제

### 📂 Support

* FAQ 챗봇
<img width="793" height="758" alt="FAQ" src="https://github.com/user-attachments/assets/763d124e-c143-4a69-b2e7-d58a73603a85" />

* FAQ 질문 관리
<img width="1448" height="758" alt="FAQ 질문 관리" src="https://github.com/user-attachments/assets/2824cdda-6cb2-4cac-8352-a9260c54ba4d" />
Django 어드민에서 질문 관리 가능

---

# 🛠 Tech Stack

| Category      | Technology                       |
| ------------- | -------------------------------- |
| Language      | Python                           |
| Backend       | Django                           |
| Database      | PostgreSQL                       |
| Frontend      | HTML, CSS, Bootstrap, JavaScript |
| Collaboration | Git, GitHub                      |

---

# 🏗️ System Architecture

(Architecture Diagram)

---

# 🗄️ Database ERD

<img width="2000" height="2100" alt="Untitled (3)" src="https://github.com/user-attachments/assets/3e0244eb-3487-4333-9be6-cc79045712f4" />

---

# 📂 Project Structure

```text
django-lms
├── board/
├── classroom/
├── course/
├── support/
├── user/
├── templates/
├── static/
└── manage.py
```

---

# 🚀 Getting Started

```bash
git clone https://github.com/dataoreo/django-lms.git

cd django-lms

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

---

