# ayven's community
2-ayven-choi-community-fe

---
## 📂 파일 구조
Community_AJ/
├── back/                             # 백엔드 코드
│   ├── controllers/                  
│   │   ├── boardController.js        # 게시판 관련 로직
│   │   ├── postController.js         # 게시글 관련 로직
│   │   └── userController.js         # 사용자 관련 로직
│   ├── json/                         
│   │   ├── comment.json              # 댓글 데이터 저장
│   │   ├── post.json                 # 게시글 데이터 저장
│   │   └── users.json                # 사용자 데이터 저장
│   ├── middlewares/                  # 요청 처리 미들웨어
│   ├── models/
│   │   ├── jsonCommentModel.js       # 댓글 모델
│   │   ├── jsonPostModel.js          # 게시글 모델
│   │   └── jsonUserModel.js          # 사용자 모델
│   ├── routes/
│   │   ├── boardRouter.js            # 게시판 라우트
│   │   ├── postRouter.js             # 게시글 라우트
│   │   └── userRouter.js             # 사용자 라우트
│   ├── utils/                        # 유틸리티 함수들
│   ├── node_modules/                 # 백엔드 의존성 모듈
│   ├── package-lock.json             # 의존성 버전 관리
│   ├── package.json                  # 백엔드 설정 파일
│   └── server.js                     # 백엔드 서버 진입점
│
├── front/                            # 프론트엔드 코드
│   ├── controllers/                  
│   │   ├── postController.js         # 게시글 관련 프론트 로직
│   │   └── userController.js         # 사용자 관련 프론트 로직
│   ├── node_modules/                 # 프론트 의존성 모듈
│   ├── public/
│   │   ├── css/                      # 스타일 파일
│   │   │   ├── add_post.css          # 게시글 추가 페이지 스타일
│   │   │   ├── board.css             # 게시판 스타일
│   │   │   ├── edit_member.css       # 회원정보 수정 스타일
│   │   │   ├── edit_password.css     # 비밀번호 수정 스타일
│   │   │   ├── edit_post.css         # 게시글 수정 스타일
│   │   │   ├── join.css              # 회원가입 스타일
│   │   │   └── login.css             # 로그인 스타일
│   │   ├── html/                     # HTML 파일
│   │   │   ├── add_post.html         # 게시글 추가 페이지
│   │   │   ├── board.html            # 게시판 페이지
│   │   │   ├── edit_member.html      # 회원정보 수정 페이지
│   │   │   ├── edit_password.html    # 비밀번호 수정 페이지
│   │   │   ├── edit_post.html        # 게시글 수정 페이지
│   │   │   ├── join.html             # 회원가입 페이지
│   │   │   ├── login.html            # 로그인 페이지
│   │   │   └── post.html             # 게시글 상세 페이지
│   │   └── js/                       # JavaScript 파일
│   │       ├── add_post.js           # 게시글 추가 기능
│   │       ├── board.js              # 게시판 기능
│   │       ├── edit_member.js        # 회원정보 수정 기능
│   │       ├── edit_password.js      # 비밀번호 수정 기능
│   │       ├── edit_post.js          # 게시글 수정 기능
│   │       ├── join.js               # 회원가입 기능
│   │       ├── login.js              # 로그인 기능
│   │       ├── menu.js               # 메뉴 기능
│   │       └── post.js               # 게시글 상세 기능
│   ├── package-lock.json             # 프론트 의존성 버전 관리
│   └── package.json                  # 프론트 설정 파일
│
└── app.js                            # 전체 프로젝트 통합 진입점


---

## 🚀 작업 진행 상황

1. **프론트 완료**
2. **서버 연결 완료**
3. **로그인 기능 완료**
4. **회원가입 기능 구현 중**

---
