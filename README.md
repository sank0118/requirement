# 요구사항 명세서 앱

1. 요구사항을 정의할 수 있습니다.

   - 프로젝트 별 요구사항 작성가능
   - 요구사항 별 기능 제목, 페이지, 상새내용, 업데이트상황,

2. 홈페이지

   - 프로젝트를 만들거나 프로젝트의 요구사항을 정의할 수 있습니다.
   - 로그인 기능이 있으면 좋음

3. 로그인 페이지

   - 이메일, 비밀번호를 통한 로그인 기능 구현 \*폼 양식 제출
   - **구글 파이어베이스 연동**
   - 회원가입 + 로그인 기능 구현

4. 프로젝트 페이지 **(CRUD 기능 구현)**

   - 요구사항을 추가할 수 있습니다.
   - 요구사항을 수정할 수 있습니다.
   - 요구사항을 삭제할 수 있습니다.

5. 요구사항
   - 기능이름
   - 해당 페이지
   - 상세 내용
     - 여러 가지가 있을 수 있습니다. Enter키로 구분하여서 목록으로
       만들어주세요.
   - 업데이트 상황
     - 수정됨
     - 수정중
     - 취소됨
   - 수정, 삭제 버튼
   - 아이디는 자동 생성
     - 요구 사항 몇개의 기능이 있는지 배열의 길이를 확인할 수
       자동 생성 / crypto를 사용하여 완전 랜덤숫자 생성

## 설치 필요 라이브러리

1. React-router-dom
2. firebase

3. papaparse - csv파일로 내보내기
