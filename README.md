## Wash Korea 프로젝트 Front-end 소개

[데모 영상](https://drive.google.com/file/d/1BbsvlZo2QaIZrlAps9iEAxLlXMc7TCYO/view?usp=sharing)

[팀명] : Wash Korea(워시 코리아)

- 러쉬코리아(https://lush.co.kr/) 클론 프로젝트 입니다.
- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론 하였습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 모두 백엔드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 개발 인원 및 기간

- 개발기간 : 2021/11/1 ~ 2021/11/12
- 개발 인원 : 프론트엔드 3명, 백엔드 2명

### 프로젝트 선정이유

- 기본적인 커머스 사이트에 필요한 핵심 기능들(로그인 및 회원가입, 제품 리스트 페이지, 제품 상세 페이지 등)을 구현해 볼 수 있어서 선택하게 되었습니다.

<br>

## 적용 기술 및 구현 기능

### 적용 기술

> - Front-End : JavaScript, React.js, SASS, HTML5/CSS
> - Common : Git, Github, Slack, Trello

### 구현 기능

#### 필수 기능 구현 목록

- 일반 회원가입 / 로그인
- Navigation, Footer
- 제품 리스트 페이지
- 제품 상세페이지

#### 담당한 페이지 목록 및 설명

##### [Footer]

- footer 레이아웃 구현
- mockup 데이터 파일 생성 및 map() 메소드를 사용하여 Footer Navbar 구현

##### [회원가입]

- 회원가입 페이지 레이아웃 구현
- mockup 데이터 파일 생성 및 map() 메소드 및 input 컴포넌트를 생성하여 input 구현
- 비밀번호 유효성 검사 (정규식 표현 사용) (영문자 + 숫자 + 특수문자 포함)
- 이메일 유효성 검사 (`@` 및 `.` 포함)
- 이메일 및 비밀번호 입력창 값의 조건 미충족 시 해당 input 하단에 에러 메세지 발생
- 필수 입력 값 미기입 후 회원가입 버튼 클릭 시 alert 을 통하여 입력 요청 알림
- 서버와 API 통신을 통한 회원가입 기능

##### [로그인]

- 로그인 페이지 레이아웃 구현
- JWT와 로컬스토리지를 사용한 로그인 기능 구현
- 로그인 유효성 검사
- Link 컴포넌트를 통하여 회원가입 창 이동 기능 구현
- 아이디 혹은 비밀번호 미기입 후 로그인 버튼 클릭 시 alert 을 통하여 입력 요청 알림
- 서버와 API 통신을 통한 로그인 기능

<br>

_아래 Reference 부분은 README.md에 꼭 포함되어야 하는 내용입니다_

## Reference

- 이 프로젝트는 [러쉬](https://lush.co.kr/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
