# 오전 스크럼

## 할 일
- 커밋 규칙 : `[날짜]_[이니셜]_[한 일]`
- 역할 분담(기능 단위)
    - 김태운 : 로그인, 회원가입, 랭킹
    - 김유경 : todoList, 점수계산

1. figma 완성
2. 점수, 항목 합의
3. DB 더미 데이터 만들기
4. 프엔, 백엔 초기화
    - 주소, 간단하게 정하기


# 미리하는 오후 스크럼
- 오늘은 피그마, 항목 합의, 프론트, 백 초기화 완료
- DB dummy data 완성, db파일 폴더에 sql있음.
- 내일 할 것 : 백엔드 구현(내일부터 주말까지)
    - 컨트롤러 설명
    - ScoreController("/api")
        - 점수계산, 랭킹 구현
    - UserController("/api-user")
        - 유저정보 CRUD

# 오후 5시 30분 기준 스크럼
- 유저 컨트롤러 초기 버전 우선 완성
    - 회원가입, 수정, 삭제, 로그인, 로그아웃, 중복아이디 방지용 체크, 마이페이지 접근시 필요한 유저 정보 로드 추가
    - datasoure.url에 쿼리 여러개 이용 위해 allowmultiqueries=true 추가.
- 현재까지의 완성은? 한 15%정도?