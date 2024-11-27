# StreamlitApp
Streamlit을 활용한 웹 애플리케이션을 Streamlit Cloud로 배포하는 것을 공부하기 위한 프로젝트

### Streamlit Cloud를 통해 웹 애플리케이션 배포하기
#### 1️⃣ github에 프로젝트 저장
- public repository로 해당 프로젝트의 private 정보를 제외한 파일을 업로드합니다.
 
⚠️ 패키지 의존성을 위한 requirements.txt 파일을 준비합니다.

#### 2️⃣ requirements.txt 작성
- 해당 프로젝트에서 사용한 라이브러리들을 모아 저장합니다. 필요시, 버전 명시도 해줍니다.

#### 3️⃣ Streamlit Cloud 사이트 접속 후 app 생성
- 해당 사이트에 접속 후 로그인합니다.
- github와 연동을 해놓으면 자동으로 new app을 누르면 본인의 repository들 중에서 배포하고 싶은 프로젝트를 선택할 수 있습니다.
- 그 후 main branch를 선택합니다.
- main file도 선택해줍니다.
- 원하는 url이 있다면 작성하고, 없다면 랜덤한 url을 생성해줍니다.

#### 4️⃣ 완성된 url을 배포합니다.
