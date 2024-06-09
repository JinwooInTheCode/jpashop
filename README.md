# 상품 판매 및 재고 관리 시스템
<p align = center>
</p>

**상품 판매 및 재고 관리 시스템**는 재고 상태를 확인하고 주문을 통해 DB와 사이트 간 상호작용을 확인할 수 있도록 하는 웹사이트입니다.

## Getting Started / 어떻게 시작하나요?

1. master 브랜치에서 프로젝트를 받아옵니다.
     ```
     git clone -b master --single-branch https://github.com/jssa428428/jpashop.git
     ```
2. H2 DB를 다운로드 받고 설치해줍니다. https://www.h2database.com<br>
3. Mac 혹은 Linux 사용자일 경우
   ```
   cd bin // 디렉토리 이동
   ``` 
   ```
   chmod 755 h2.sh // 권한 설정
   ```
   ```
   ./h2.sh // 실행
   ```   
4. Windows 사용자일 경우
   ```
   cd C:\Program Files (x86)\H2\bin // cmd를 열고 H2가 설치된 경로로 이동
   ``` 
   ```
   h2.bat // 실행
   ```   
5. JDBC URL에 jdbc:h2:~jpashop를 입력하고 연결을 클릭해줍니다.
<img src = "https://github.com/jssa428428/jpashop/assets/60772265/27348741-5807-4c19-8669-a8127dbeea84">

6. 본인 PC의 홈폴더(C:\Users\[사용자명])로 가서 jpashop.mv.db 파일이 생성되었는지 확인합니다.
7. 생성되었다면 JDBC URL에 jdbc:h2:tcp://localhost/~/jpashop을 입력해주시고 계속해서 이 방식으로 접속하면 됩니다.

## Prerequisites / 선행 조건

아래 사항들이 설치가 되어있어야합니다.

```
Java 17 이상, H2, IntelliJ
```

## Function / 기능
+ 회원 가입
+ 회원 목록 조회
+ 상품 등록
+ 상품 목록 조회
+ 상품 수정
+ 상품 주문
+ 상품 주문 목록 조회
+ 상품 주문 내역 검색
+ 상품 주문 취소

## Front-End Technology / 프론트 기술
+ HTML5
+ Thymeleaf
+ Bootstrap 5.3.3

## Back-End Technology / 백엔드 기술
+ Java Spring Boot 3.2.4
