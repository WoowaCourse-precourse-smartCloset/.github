# 코디'ing - 날씨 기반 맞춤형 의상 추천 시스템

---

## 프로젝트 이름
**코디'ing** (SmartCloset)

---

## 소개
코디'ing은 사용자의 현재 위치와 실시간 날씨 정보를 기반으로, 상황에 맞는 의상을 추천해주는 웹 애플리케이션입니다. **GPT-4** 기술을 활용해 사용자의 스타일과 선호를 반영한 맞춤형 추천을 제공하여 매일 아침 옷차림을 고민하는 시간을 절약하고, 자신 있게 하루를 시작할 수 있도록 돕습니다.

---

## 프로젝트 배경
일교차가 큰 날씨 속에서 적절한 옷차림을 결정하는 데 어려움을 겪는 사용자를 위해 설계된 프로젝트입니다. GPS와 실시간 기상 데이터를 활용하여 현재 위치에 맞는 최신 날씨 정보를 제공하며, 개인화된 옷차림 추천으로 기온 변화에 따른 불편함을 줄이고자 합니다. 

특히 패션 경험이 적은 사용자도 직관적인 인터페이스를 통해 쉽게 사용할 수 있도록 설계되었습니다.

---

## 주요 기능
1. **날씨 기반 의상 추천**  
   - 실시간 기상 데이터를 활용하여 상황에 맞는 맞춤형 의상을 추천합니다.
   - 사용자의 스타일과 선호를 분석해 더욱 개인화된 추천을 제공합니다.
   - 해시태그를 통해 더 직관적으로 볼 수 있습니다.

2. **피드 기능**  
   - 다른 사용자의 코디를 참고하거나 자신의 스타일을 공유할 수 있습니다.  
   - 피드에는 날씨 이모티콘이 표시되어, 해당 코디가 어떤 날씨에 적합한지 쉽게 확인할 수 있습니다.
   - 해시태그를 통해 더 직관적으로 볼 수 있습니다.

3. **로그인 및 사용자 관리**  
   - 이메일 기반 회원가입과 특수문자 및 숫자 포함 비밀번호를 통해 더 고도화 된 비밀번호를 구축 할 수 있습니다.
   - 이메일, 비밀번호, 닉네임으로 간단하게 회원가입 할 수 있습니다.

4. **실시간 날씨 확인**  
   - 단기 날씨 API를 통해 현재 위치의 실시간 날씨를 제공합니다.  
   - 날씨 변화가 잦은 지역의 사용자에게 큰 도움을 줍니다.

---

## 개발 환경

| Category              | Tech Stack |
|-----------------------|------------|
| **Language / Framework** | ![Kotlin](https://img.shields.io/badge/Kotlin-007396?style=flat-square&logo=kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Database**          | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![Spring Data JPA](https://img.shields.io/badge/Spring%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white) |
| **Etc Tools**         | ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-FF6C37?style=flat-square&logo=swagger&logoColor=white) |
---

## 기대효과 및 활용
- **효율적인 시간 관리:** 매일 아침 옷차림을 고민하는 시간을 줄여 바쁜 일상 속에서 효율적으로 시간을 활용할 수 있습니다.  
- **패션 접근성:** 패션 경험이 적은 사용자도 적절한 스타일을 선택할 수 있도록 돕습니다.  
- **커뮤니티 형성:** 피드를 통해 다양한 패션 아이디어를 공유하고, 사용자 간 상호작용을 촉진합니다.  
- **개인화된 경험 제공:** 사용자 스타일을 반영한 맞춤형 추천으로 패션에 대한 관심을 높이고, 자신감을 키울 수 있습니다.

---

## 깃허브
[기존 레포지토리]
- **프론트엔드 레포지토리:** [GitHub Frontend Repo](https://github.com/OSP-smartcloset/Frontend-repo)  
- **백엔드 레포지토리:** [GitHub Backend Repo](https://github.com/OSP-smartcloset/Backend_repo) 


[리팩토링 한 레포지토리]
- **프론트엔드 레포지토리:** [GitHub Frontend Repo](https://github.com/WoowaCourse-precourse-smartCloset/Frontend)  
- **백엔드 레포지토리:** [GitHub Backend Repo](https://github.com/WoowaCourse-precourse-smartCloset/Backend) 

---

## 주요기능 및 구조도
<img width="343" alt="image" src="https://github.com/user-attachments/assets/8620a032-8010-4795-92ac-f449160a2605">


---

## 시스템 구성 및 아키텍처
<img width="341" alt="image" src="https://github.com/user-attachments/assets/3a04634b-43b9-4c4a-b1f5-a4db03619e3f">


---


## 기타
이 프로젝트는 일상 속에서 옷차림 고민을 덜어주고, 사용자의 스타일에 맞는 패션 경험을 제공합니다. 패션 초보자부터 관심이 많은 사용자까지 누구나 활용할 수 있는 시스템입니다. 
