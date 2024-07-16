# Memory
Mobile application for tagging & searching photos with AI features
# 협업 세팅
협업을 위해 본 저장소를 [obsidian](https://obsidian.md/)의 backup으로 설정하는 방법을 설명합니다.
본 문서에서 설명하는 도구에 익숙하지 않을 경우, 지시를 상세히 읽고 따라주세요.
## 도구 소개 및 설치
### github
git 저장소를 원격 으로 저장해 다른 사람과 동일한 파일을 가지고 협업할 수 있게 도와주는 사이트.
[github](https://github.com/) 회원가입을 완료하세요.
### git
버전 관리 및 협업을 도와주는 툴
원래는 처음 사용하기에 진입장벽이 있지만, 본 프로젝트의 협업에는 많은 기능이 필요하지 않으므로 여기서는 자세히 설명하지 않습니다.
#### git 설치
[링크](https://taewow.tistory.com/13)를 따라서 git을 설치합니다.
이 때, 사용자명과 이메일은 github 아이디/이메일과 동일하게 설정합니다.
(기본적으로 사이트의 사진을 따라 설치하나, 막히는 부분이 있다면 derick321@naver.com으로 문의 바랍니다.)
### 옵시디언
마크다운 문법을 사용하는 문서 작성 도구. 사용자에 따라 다양한 커스터마이징이 가능합니다.
각 Vault가 하나의 폴더로 관리되고 하나의 문서는 단순한 텍스트 파일이기 때문에, 다른 플랫폼과 호환성이 좋다는 장점이 있습니다.
마크다운 문법에 대해서는 [나무위키 - 마크다운](https://namu.wiki/w/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)을 참조하세요.익숙해진다면 빠른 속도로 고도로 구조화된 문서 작성이 가능하니, 생각이나 지식을 글로 정리하는 데 관심이 있다면 배워보시는 걸 추천드립니다.
#### 옵시디언 설치
[링크](https://thinking-lab.tistory.com/513)에 접속하여 설치 파일 다운로드 후 실행하여 설치합니다. 일단은 설치까지만 진행하고, 저장소 연결은 이후에 진행합니다.
## 저장소 연결
본 깃허브 저장소를 로컬 옵시디언에 연결합니다.
### 1. 본 저장소 다운받기
현재 홈페이지의 맨 위로 스크롤 -> 오른쪽 위의 초록색 `<>code` 버튼 클릭 -> Download ZIP 클릭하여 다운로드 -> 다운받은 압축파일을 원하는 위치에 풀기 (저는 일반적으로 문서 폴더에 몰아넣는 편입니다.)
![[스크린샷 2024-07-16 오후 4.07.04.png]] *버튼은 이렇게 생겼습니다. 아주 사랑스러운 녀석이죠.*
### 2. 옵시디언과 연결하기
옵시디언을 켭니다. 설치 과정에서 보관소를 만들지 않았다면, 아래와 같은 화면이 보입니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348989476-d9f08985-29d6-45f2-bd5b-c92c16d27ec7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY0NjUsIm5iZiI6MTcyMTExNjE2NSwicGF0aCI6Ii81NTkyMjczNy8zNDg5ODk0NzYtZDlmMDg5ODUtMjlkNi00NWYyLWJkNWItYzkyYzE2ZDI3ZWM3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NDkyNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ4MjMzODdmNjlmNzg0YmE4YWZkMTk3N2JkNDQzMWE3MWRiNzMzY2MzMzk4MDZkZmU1OTc1NDY1NzU0ZGQwNzkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ztWMUEu--85_WjdFWWnFQAnSHOe2VJbpa_fzrDVke7M">
1) "Open" 선택 > 아까 압축을 풀었던 폴더를 선택하여 vault를 엽니다. 꼭 **"memory" 폴더 자체**를 선택한 후에 확인을 눌러 주세요.
<img src="https://private-user-images.githubusercontent.com/55922737/348990783-990ec321-8613-425d-a758-cfa080c12b85.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY0NjMsIm5iZiI6MTcyMTExNjE2MywicGF0aCI6Ii81NTkyMjczNy8zNDg5OTA3ODMtOTkwZWMzMjEtODYxMy00MjVkLWE3NTgtY2ZhMDgwYzEyYjg1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NDkyM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTI5MmJjNTE5OTZjZTcxNGQ4NGEyYjcyMTY1NWEyMGMwNDlhMTIxODUzNTE4MDczZmUzOWY2YTAwMjQ4YWVhYjUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ytHRU-roNn73UBk3enzhUl6zjdDtxSXDgPhMEDMdFiY">
2) 만약 위처럼 사이드바에 README 파일이 보이지 않는다면, 의도한 것과 다른 보관소에 들어온 것입니다. 왼쪽 하단의  ![[스크린샷 2024-07-16 오후 4.01.19.png]] 아이콘 클릭 후 아래처럼 "Manage vaults..."를 클릭해 1)을 다시 수행합니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348989511-f4a69615-7d42-4739-ab8b-fb5b6904d01f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY0NjUsIm5iZiI6MTcyMTExNjE2NSwicGF0aCI6Ii81NTkyMjczNy8zNDg5ODk1MTEtZjRhNjk2MTUtN2Q0Mi00NzM5LWFiOGItZmI1YjY5MDRkMDFmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NDkyNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTZhMWUxMzBkMzk1MjEzZDMyMmIxMjY0NjMxOWJlMzBlNmRmZTliZmVhMTcyMWViMWZiOTg0MTY1ZTEwMWQ2MmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.xmY53EctO1xrusO-dnR6ry2OGo3MhDayvrISkVgMCvE">
### 3. git 플러그인 설치하기
1) **설정 진입**
	왼쪽 아래의 요 톱니바퀴 버튼을 눌러 설정에 진입합니다.
	<img src="https://private-user-images.githubusercontent.com/55922737/348989469-79cc638d-64ff-4677-bbc9-87d0dbac21c7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTYzMjQsIm5iZiI6MTcyMTExNjAyNCwicGF0aCI6Ii81NTkyMjczNy8zNDg5ODk0NjktNzljYzYzOGQtNjRmZi00Njc3LWJiYzktODdkMGRiYWMyMWM3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NDcwNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTljNGY2YzY4YTUxZDJlMTkwZTkzOWEwYThiZDBjNDYxZTc3MjI5ZDg3ZjJjMTIxNjNiM2Q3YzMwNTI4OGYzZDUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.grJdkxaySpBlTd8KD_wPzx4g-jWMvfZD5KdsyGyMhsI">
2) **커뮤니티 플러그인 활성화**
	"Community plugins"에서 "Turn on community plugins"를 클릭해 외부 플러그인을 활성화합니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348989488-c70fd80e-d2c6-41cf-85b3-f16950ca8ab8.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY0NjUsIm5iZiI6MTcyMTExNjE2NSwicGF0aCI6Ii81NTkyMjczNy8zNDg5ODk0ODgtYzcwZmQ4MGUtZDJjNi00MWNmLTg1YjMtZjE2OTUwY2E4YWI4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NDkyNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTI2MTBhY2U2YmQ4NzgxN2JmODNmZmE1ZWYwNTU1ODM5YTUzMGRmZDU1MjJhNTVjNmM0ZDYxNzZmYzU4NzE4NzEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.yWGaH9ZyLINJM2yh69MfR5S1VyrqE6jBSvDF7tLaWKw">
3) "Community plugins" 탭의 "Browse"를 눌러 플러그인을 검색합니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348989500-b822a5e3-97da-4e72-a8ea-a3a8cea26274.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY0NjUsIm5iZiI6MTcyMTExNjE2NSwicGF0aCI6Ii81NTkyMjczNy8zNDg5ODk1MDAtYjgyMmE1ZTMtOTdkYS00ZTcyLWE4ZWEtYTNhOGNlYTI2Mjc0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NDkyNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY4OTJjMzJhZDlkN2Y3ZDA2MjQyN2UxYzZlYmZjNTAxYTJmYTczOGM0NjIzN2ViMmVlMWI2ODYyYzQwYWNmODkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.CPmv5438t1VdUKZqiogtsQIk8ks9I0uJwRwK2WDKsYY">
4) "git" 플러그인을 검색하여 "install"을 눌러 설치합니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348994086-4ef1c3d8-df3a-4f6f-846e-cb23fd6bb2d5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTcwMTYsIm5iZiI6MTcyMTExNjcxNiwicGF0aCI6Ii81NTkyMjczNy8zNDg5OTQwODYtNGVmMWMzZDgtZGYzYS00ZjZmLTg0NmUtY2IyM2ZkNmJiMmQ1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NTgzNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTVjMDE1ZGVhM2M4MjJmYjRhN2Q1YzAwMzAwNWQ0ZWM3MGVhY2QxMmVjOWE4NzUwNDFhNGY1YzdhNjBlNWY4NjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ZtlQvqp99_Sa-F-H6yV9ZIaA7ajbfXe_RV9EwqXIjqc">
5) 설치가 완료되면, "Enable"을 클릭해 활성화합니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348992987-e5a09a8d-07a9-4543-8cd6-7c68d3c95ccc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY4MzQsIm5iZiI6MTcyMTExNjUzNCwicGF0aCI6Ii81NTkyMjczNy8zNDg5OTI5ODctZTVhMDlhOGQtMDdhOS00NTQzLThjZDYtN2M2OGQzYzk1Y2NjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NTUzNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWIxZGY2YzkwN2ZjNWM1Yjk4MjJmZGRhNDA5NmFkOWYxNmUxMjJmZTNhMDY1MmExYTFmZDBkMjEyMzZiMzU3YWUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.37DbmV0B00iOhCDszE8C7TaGbM4zZu9iSPzM6PkVrf4">
6) "Options"를 눌러 아래와 같이 환경설정을 진행해 줍니다.
<img src="https://private-user-images.githubusercontent.com/55922737/348992977-aeea7660-eca3-4cd5-88c8-e939456b264b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY4MzQsIm5iZiI6MTcyMTExNjUzNCwicGF0aCI6Ii81NTkyMjczNy8zNDg5OTI5NzctYWVlYTc2NjAtZWNhMy00Y2Q1LTg4YzgtZTkzOTQ1NmIyNjRiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NTUzNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgxZjI2ZGU0NmY5OGI4ZjNhZmQ1MWFhZDdiZTg4NDBhYjgwYjQ3MTMzMjA5M2ZlYTlhNTkxNjdjZmIyMTMyZmEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.KU0KIRVZwXhIFJQk6gljsBJjWdOwoPmhgi3Vy5RVONE">
<img src="https://private-user-images.githubusercontent.com/55922737/348992991-79874eed-69a0-4a94-a9cc-73d7ef6d9813.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY4MzQsIm5iZiI6MTcyMTExNjUzNCwicGF0aCI6Ii81NTkyMjczNy8zNDg5OTI5OTEtNzk4NzRlZWQtNjlhMC00YTk0LWE5Y2MtNzNkN2VmNmQ5ODEzLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NTUzNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY2NmUwMWM2MzlhNjNhZmY5MGQxYTcyMjY4NjgzZDNhNmJiOTk1NTIyZTk3OWYwNDAyZGM0MDA3NDQ0MjE2MTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.pMJDRW-jqTjxsa5qg_6-E36RFmqLDw17foqbYFXAXqQ">
<img src="https://private-user-images.githubusercontent.com/55922737/348992995-9fdc575a-0cdf-406f-95bc-f0f67cf19f7f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjExMTY4MzQsIm5iZiI6MTcyMTExNjUzNCwicGF0aCI6Ii81NTkyMjczNy8zNDg5OTI5OTUtOWZkYzU3NWEtMGNkZi00MDZmLTk1YmMtZjBmNjdjZjE5ZjdmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzE2VDA3NTUzNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTA0YmFjNjY3MDA1ZjM5ZWMxYWNkNjJkMTQzZjE0MDMzNDFhOTRlMzBkMjI4MmNlZGQyNDAwYzUzYWVkNDUwMzUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.yUqlNUFkjdcU5xhz4pTVK-oRBZt9FpaRrWzHdtTfnPY">
- "Dongseop"이라고 쓰인 부분은 닉네임 같은 것이니 마음대로 바꿔도 좋습니다.
와! 이제 당신은 저와 협업할 준비를 마쳤습니다. 파일이 더 빠른 주기로 업데이트되기를 원하신다면 **"Vault backup interval"** 설정을 변경하면 됩니다. (설정 > community plugins > git에서 설정할 수 있음)
# 기타 자료
[나무위키 - 마크다운](https://namu.wiki/w/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)