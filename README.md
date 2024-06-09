<h1>상품 판매 및 재고 관리 시스템 실행 방법</h1>
<h2>어떻게 실행하나요?</h2>
1. master 브랜치에서 프로젝트를 받아옵니다.
   ```
    git clone -b master --single-branch https://github.com/jssa428428/jpashop.git
   ```
<br>
2. H2 DB를 다운로드 받고 설치해줍니다. https://www.h2database.com<br>
3.1. Mac 혹은 Linux 사용자일 경우<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1) 디렉토리 이동
   ```
    cd bin
   ```
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2) 권한 설정
   ```
    chmod 755 h2.sh
   ```
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3) 실행
   ```
    ./h2.sh
   ```
<br>
3.2. Windows 사용자일 경우<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1) cmd를 열고 H2가 설치된 경로로 이동 예) cd C:\Program Files (x86)\H2\bin<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2) h2.bat 실행<br>
4. JDBC URL에 jdbc:h2:~jpashop를 입력하고 연결을 클릭해줍니다.<br>
5. 본인 PC의 홈폴더(C:\Users\[사용자명])로 가서 jpashop.mv.db 파일이 생성되었는지 확인합니다.<br>
6. 생성되었다면 JDBC URL에 jdbc:h2:tcp://localhost/~/jpashop을 입력해주시고 계속해서 이 방식으로 접속하면 됩니다.<br>
