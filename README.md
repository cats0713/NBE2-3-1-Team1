# programmers_coffee
프로그래머스 프로머스 1차 과제 클론(사이렌 오더)

---

## 프로젝트 개요

- 24.11.11 ~ 24.12.10 [약 한달]
- 

---

## 기획의도 - 다같이

- 
- 
- 

---

## 주요 기능

- `세부기능`
    
    회색은 우선순위 매우 낮음 💡
    
    ### 사용자 (User)
    
    1. **회원 등록**
        - **회원 가입**
            - 이메일/전화번호 기반의 회원 가입
            - 필수 정보 (이메일/ 비밀번호/ 이름) 등
            - 이메일 인증/ 전화번호 인증 절차
            
    2. **비밀번호 리셋/ 회원 탈퇴/ 비활성화/ 아이디 변경**
        - **비밀번호 리셋**
            - 이메일 또는 SMS 비밀번호 재 설정 링크 발송
            - 보안 질문/ 이메일 확인 등을 통한 인증
        - **회원 탈퇴**
            - 사용자가 직접 요청하거나 관리자가 강제 탈퇴 시킬 수 있는 기능
            - 탈퇴 시 데이터 삭제 처리
        - **비활성화**
            - 비 활성화된 계정은 로그인이 불가능
            - 사용자에게 알림을 보내며, 관리자만 활성화 가능
        
    3. **회원 정보 조회 및 수정**
        - **회원 정보 조회**
            - 사용자 본인만 본인의 정보 조회 가능(이름, 이메일. 연락처 등)
        - **회원 정보 수정**
            - 이름 연락처, 주소 등 수정 가능
        - **프로필 사진 변경**
            - 사용자가 프로필 사진을 업로드 하거나 수정
    
    1. **로그인**
        - **로그인 및 자동 로그인**
            - 이메일/전화번호 기반 로그인 및 소셜 로그인.
    2. **주문 및 결제**
        - **메뉴 조회**
            - 카테고리 별 메뉴 보기
            - 제품의 상세 정보(재료, 영양 성분, 알레르기 정보)
        - **주문 기능**
            - 커스텀 옵션 선택
                - 샷 추가, 시럽 변경 등
            - 장바구니 관리
                - 선택한 메뉴의 추가, 제거 및 옵션 변경
            - 빠른 재주문
                - 이전 주문 내역을 기반으로 빠르게 재주문
        - **결제**
            - 결제 옵션 ( 카드, 간편 결제, 포인트 사용 등 )
            - 할인 및 쿠폰
            - 결제 내역 관리
        - **주문 상태 확인 및 알림**
            - 주문 진행 상황 확인
            - 주문 상태 업데이트 알림
    
    ### 관리자 (Admin)
    
    1. **회원 관리**
        - 회원 탈퇴 및 비활성화 처리
    2. **메뉴 및 주문 관리**
        - 메뉴 추가 및 수정
        - 옵션 관리 (추가 옵션)
        - 주문 모니터링
        - 결제 확인
    

---

## 팀소개

- 팀장: 유아현 [ 총괄, 아키텍쳐 설계, API 명세서, 나머지 페이지 혹은 너무 양이 많으면 나눠 갖기, 초기데이터 ]
- 팀원: 김소연 [ 시퀀스 다이어그램, API 명세서, 주문 및 결제 ]
- 팀원: 정도현[ DB 설계, API 명세서, 회원관리(가입 및 수정) ]
- 팀원: 최지영 [ 시퀀스 다이어그램, API 명세서, 메뉴조회, 주문상태 확인 ]
- 팀원: 허정현 [ 프로젝트 순서도, 시퀀스 다이어그램, API 명세서, 관리자 권한 및 전용페이지 ]


소연 - 멤버
정현, 지영 - 상품
도현, 아현 - 주문

---

## 아키텍쳐

- `아키텍쳐`
    <img width="785" alt="image" src="https://github.com/user-attachments/assets/7c12bd1b-a304-46b9-8b12-98a1ebc2c69c">


---

## 개발환경

- 앱 : JAVA
- 서버 : Apache, html
- DB : Mysql
- postman

---

## 구성 라이브러리 -차차채우는걸로 정리

- 

---

## 프로젝트 순서도 - 허정현

- `순서도`
  ![image2](https://github.com/user-attachments/assets/a60df83c-bb6f-4391-8a21-af842047d2f8)
  ![image3](https://github.com/user-attachments/assets/b3d3e9ee-4a5c-4c5a-bd92-6e994d5d0ab1)

    


**수정사항이 생기면 추가로 적거나 추가할게여** 

- 적어주세여

---

## usecase

- `USECASE`
    ![image4](https://github.com/user-attachments/assets/ec47c362-b521-416c-a71c-fb33918ab057)

---

## ERD

- `도면`
    
    ![ima![image5](https://github.com/user-attachments/assets/9095b18f-be44-4e0b-95ec-44a686488f17)

---

## 시퀀스 다이어그램 - 김소연, 최지영, 허정현

- `다이어그램`
    
    
    - 회원가입
        
        ![image](https://github.com/user-attachments/assets/6804adc9-ab7b-4a69-b149-2608f90315f8)

        
    - 비밀번호 리셋
        
        ![image](https://github.com/user-attachments/assets/2e6869c9-95eb-44fa-ab90-446e47d67ded)

        
    - 계정 비활성화
        
       ![image](https://github.com/user-attachments/assets/ae186aa9-d29d-44c6-81ac-c841a094e1f6)

        
    
    - 메뉴 조회
        
       ![image](https://github.com/user-attachments/assets/826f9abc-b49d-4ecd-8a0b-19a21553fa08)

        
    - 장바구니 관리
        
      ![image](https://github.com/user-attachments/assets/05018296-22bc-416d-ac28-315d9bf50bd3)

        
    - 주문 및 결제
        
        ![image](https://github.com/user-attachments/assets/c750f79d-3652-4fc7-b863-9dac972e5b28)

        
    - 옵션 추가 및 수정 (관리자)
        
       ![image](https://github.com/user-attachments/assets/a650158d-940b-4593-841c-d8b11db8ef42)

        
    - 쿠폰 발행(관리자)
        
       ![image](https://github.com/user-attachments/assets/e73bf46c-27db-479b-a296-a8422036b803)

        
    
    - 로그인/로그아웃
        
       ![image](https://github.com/user-attachments/assets/211771b8-848a-418c-b4d8-c8af39838c67)

        
    - 회원 탈퇴
      
        ![image](https://github.com/user-attachments/assets/fc971674-d36c-41a0-9cc9-d33ea6686fab)

        
    - 회원정보 조회/수정
        
        ![image](https://github.com/user-attachments/assets/1184fa37-b3cc-44ef-841d-2e8db2fe1d33)

        
    
    - 커스텀 옵션 선택
        
        ![image](https://github.com/user-attachments/assets/7c49372b-b239-4895-b95f-2b22c79f2ffc)

        
    - 재주문 요청
        
        ![image](https://github.com/user-attachments/assets/00bf1c82-8b99-40ab-8e15-aa3bbd40be08)

        
    - 메뉴 추가 및 수정 (관리자)
        
        ![image](https://github.com/user-attachments/assets/4faa7ac6-361c-4321-acc0-cb38ab79b90c)

        
    - 주문 모니터링 (관리자)
        
       ![image](https://github.com/user-attachments/assets/cbfd0bb4-ce00-463e-9edb-3fb5d0e4a27b)

        
    

---

## API 명세서 - 각자

- `API`
    

---

# 기타
