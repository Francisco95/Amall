# SpringBoot-Project-Amall

SpringBoot + JSP를 이용한 커플 쇼핑몰

## 프로젝트 소개

스페인어의 사랑을 뜻하는 Amor(아몰)과 Mall을 합친 커플 쇼핑몰

## 프로젝트 목적

- 커플인 회원들이 물품을 2개씩 구매하여 더 싼 가격에 구입할 수 있는 서비스 제공
- 이벤트로 AM + all 오전에 제품 타임 세일 서비스 제공
- 매칭 기능을 이용하여 매칭 상대의 개인정보를 모르더라도 물품 구입할 수 있는 서비스 제공
- 매칭 상대의 위시리스트를 볼 수 있는 서비스 제공
- 애인이 없는 회원들이 소통하고 자신을 어필할 수 있는 서비스 제공(미구현)

## 개발 기간

- 2023-02-21 ~ 2023-03-13 (15일)

## 개발 인원

- 팀장 이승주 - 프로젝트 총괄, 화면 구현, 기능 구현, 기능 설계
- 팀원 서단우 - 화면 구현, 기능 구현, DB 설계
- 팀원 조희은 - 화면 설계, 화면 구현, 산출물 관리, 일정 계획

## 개발 환경

- Java 8
- JDK 1.8.0
- IDE : STS 4.18.1
- Framework : Springboot 3.0.3
- Database : Oracle DB
- ORM : Mybatis

## 주요 기능 및 화면

**메인화면**

<details>
<summary>더보기</summary>
  
![메인화면](https://github.com/Francisco95/Amall/assets/77893146/b7759237-bfb8-42e8-bc1c-d9cb066e4f9d)
</details>  



**로그인**

- ID, Pwd 일치 확인
- ID, Pwd 찾기
- 로그인 세션 생성

<details>
<summary>더보기</summary>

![로그인](https://github.com/Francisco95/Amall/assets/77893146/3bc0efad-7020-4210-a7ac-955d0d2c9834)

</details>



**회원가입**

- ID, Email 중복 체크
- 우편번호 찾기

<details>
<summary>더보기</summary>

![회원가입](https://github.com/Francisco95/Amall/assets/77893146/107a80f0-c51e-4dc8-8eca-cda265e78f55)

![주소입력모달](https://github.com/Francisco95/Amall/assets/77893146/044f204f-9113-4e9d-8db9-6f5aa07f8939)

</details>



**마이페이지**

- 로그인 세션 Null 체크

<details>
<summary>더보기</summary>
  
![마이페이지](https://github.com/Francisco95/Amall/assets/77893146/95946b40-ccd9-42d6-b96c-58a4faa96de0)

</details>



**매칭페이지**

- 매칭 알림 리스트 세션 생성
- 매칭 수락 시 매칭 상대 DB 저장
- 매칭 수락 및 거절 시 해당 매칭 알림 제거

<details>
<summary>더보기</summary>

![매칭페이지_매칭있음](https://github.com/Francisco95/Amall/assets/77893146/5a5f9c5e-0d1c-4440-8596-c7be46545b05)
![매칭페이지_매칭없음](https://github.com/Francisco95/Amall/assets/77893146/878bc31e-c5fe-465c-a676-eb24ce73d1bb)
</details>



**개인정보수정**

- 회원 정보 업데이트 및 삭제
- 매칭 알림 전송 시 본인 및 상대의 매칭 상태 확인, 입력 상대가 본인인지 확인, 이미 보낸 상대인지 확인, 존재하지 않는 상대인지 확인 후 해당 없을 시 매칭 알림 전송

<details>
<summary>더보기</summary>
  
![개인정보수정](https://github.com/Francisco95/Amall/assets/77893146/2137b1c4-4c76-47ab-8c06-36d22e5efc4a)
</details>



**위시리스트**

- 매칭 상대가 있을 경우 나와 매칭 상대의 위시리스트 5개까지 출력

<details>
<summary>더보기</summary>
  
![위시리스트](https://github.com/Francisco95/Amall/assets/77893146/2a9cce44-a7e0-47ea-8778-b1f2b56d7e2c)
</details>
