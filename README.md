<div align="center">

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

* 회원가입 및 이메일 인증
<img width="1157" height="464" alt="중복확인" src="https://github.com/user-attachments/assets/fe1fd4f1-639c-4bae-a44d-80d78e6a4099" />
<img width="1412" height="1042" alt="회원가입 및 이메일 인증" src="https://github.com/user-attachments/assets/41aa01a5-da7a-4d38-bc2c-b8423c9d5313" />

* 아이디 비밀번호 찾기
<img width="577" height="501" alt="아이디 찾기" src="https://github.com/user-attachments/assets/c29195d9-68c9-47e1-8a85-4d69f9d47223" />
<img width="757" height="614" alt="비밀번호 재설정 및 로그인" src="https://github.com/user-attachments/assets/2d2bdad3-e55b-4876-8bcc-04585e16e6fd" />

* 사용자 권한 관리

### 📚 Course

* 강의 생성 및 조회
* 강의실(Classroom) 관리

### 📝 Board

* 게시글 작성
* 게시글 수정 및 삭제
* 댓글 기능

### 📂 Support

* 공지사항
* 학습 자료 공유

---

# 🛠 Tech Stack

| Category      | Technology                       |
| ------------- | -------------------------------- |
| Language      | Python                           |
| Backend       | Django                           |
| Database      | MySQL                            |
| Frontend      | HTML, CSS, Bootstrap, JavaScript |
| Collaboration | Git, GitHub                      |

---

# 🏗️ System Architecture

(Architecture Diagram)

---

# 🗄️ Database ERD

(ERD Image)

---

# 💾 Database Design

관계형 데이터베이스를 기반으로 사용자와 강의, 게시판 간의 관계를 설계했습니다.

* Django ORM을 활용한 데이터 모델링
* Foreign Key 기반 엔티티 관계 설계
* 관계형 데이터베이스 기반 CRUD 구현
* 사용자 권한에 따른 데이터 접근 제어

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

# 📸 Demo

| Login | Course |
| ----- | ------ |
| 이미지   | 이미지    |

| Board | Classroom |
| ----- | --------- |
| 이미지   | 이미지       |

---

# 📚 What I Learned

* Django MTV 아키텍처 기반 웹 애플리케이션 개발 경험
* Django ORM을 활용한 관계형 데이터베이스 설계 및 CRUD 구현
* Git을 활용한 협업과 브랜치 관리 경험
* 사용자 권한을 고려한 백엔드 기능 설계
* 팀 프로젝트를 통한 협업 및 문제 해결 경험
