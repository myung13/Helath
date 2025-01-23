# 운동 기록 관리 시스템 🏋️‍♂️

## 📖 프로젝트 소개
운동 기록 관리 시스템은 개인 운동 기록을 체계적으로 관리하기 위한 웹 애플리케이션입니다.  
회원 가입, 로그인, 유산소 및 무산소 운동 기록 생성, 수정, 삭제와 같은 기능을 제공합니다.

---

## 🚀 주요 기능

### 1️⃣ 사용자 관리
- **회원가입**: 사용자의 이름, 전화번호, 비밀번호를 입력받아 새로운 회원을 생성합니다.  
- **로그인**: Spring Security를 사용하여 전화번호와 비밀번호 기반 인증을 처리합니다.  

#### 관련 코드
- **Entity**: `Member`  
- **Repository**: `MemberRepository`  
- **Service**: `MemberService`

---

### 2️⃣ 운동 기록 관리

#### 🏃‍♂️ 유산소 운동
- **기록 생성**: 유산소 운동 타입, 이름, 시간, 칼로리를 기록합니다.  
- **기록 수정**: 유산소 운동 정보를 수정할 수 있습니다.  
- **기록 삭제**: 특정 유산소 운동 기록을 삭제합니다.  

#### 🏋️‍♀️ 무산소 운동
- **기록 생성**: 무산소 운동 타입, 이름, 무게, 반복 횟수, 세트를 기록합니다.  
- **기록 수정**: 무산소 운동 정보를 수정할 수 있습니다.  
- **기록 삭제**: 특정 무산소 운동 기록을 삭제합니다.  

#### 공통 기능
- 특정 날짜 및 주간 운동 기록 조회  
- 날짜와 운동 종류별 기록 조회  

#### 관련 코드
- **Entity**: `ExerciseLog`  
- **Repository**: `ExerciseLogRepository`  
- **Service**: `ExerciseLogService`

---

## 🛠️ 기술 스택

### Back-end  
<img src="https://github.com/user-attachments/assets/75c4bc4c-0867-42e7-b2d7-33da085be553" alt="Java" width="50"/>  
**Java**: 백엔드 로직을 구현하는 데 사용한 주요 프로그래밍 언어입니다.  

<img src="https://github.com/user-attachments/assets/77a6edd1-85f0-4677-92c9-a1553c1ae9e4" alt="Spring Boot" width="50"/>  
**Spring Boot**: 효율적인 RESTful API 개발과 애플리케이션 구성을 지원합니다.  

<img src="https://github.com/user-attachments/assets/cf762c34-60df-4206-b42e-f6c6cd0fc6f0" alt="Spring Security" width="50"/>  
**Spring Security**: 사용자 인증 및 권한 관리를 처리합니다.  

---

### Database  
<img src="https://github.com/user-attachments/assets/c1fd1d37-aa9f-4f50-bce9-baf06e1f8d81" alt="MySQL" width="50"/>  
**MySQL**: 사용자와 운동 기록 데이터를 저장합니다.  

---

### View  
<img src="https://github.com/user-attachments/assets/a7f0fbaa-51da-4792-b0dd-d69320c3a2e2" alt="Thymeleaf" width="50"/>  
**Thymeleaf**: HTML 템플릿 엔진으로 프론트엔드와 백엔드 데이터를 연동합니다.  

---

### Build Tool  
<img src="https://github.com/user-attachments/assets/12345678-gradle-logo.png" alt="Gradle" width="50"/>  
**Gradle**: 의존성 관리와 빌드 자동화를 지원합니다.  

---

## 🖼️ 주요 화면

### 회원가입 및 로그인 창
![회원가입 로그인창](https://github.com/user-attachments/assets/36bf7e49-fc8e-489c-bdde-d6f3d469fbaf)

### 운동 기록 입력 및 조회
![운동기록 입력, 조회](https://github.com/user-attachments/assets/301ede3e-40ea-4a25-a7f0-9b63a531682b)

### 운동 기록 수정 전/후
![운동 기록 수정 전, 후](https://github.com/user-attachments/assets/3b5b56f7-d543-4d9c-95de-28d3d7867254)
