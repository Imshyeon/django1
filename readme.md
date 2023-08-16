# git 버전관리 기초
1. Working Directory(작업한 파일 상태) -> `git add` -> Staging Area(커밋할 파일 상태 목록) -> `git commit` -> Repository
2. 사용자 설정
    - git config --global user.email "kzoen0040@naver.com"
    - git config --global user.name "zoe"

예시
- git add index.html => staging area에 추가히기 위해 사용. 
    - untracked 상태의 파일을 staged로 변경
    - modified 상태의 파일을 staged로 변경
    - git add . => 현재 경로의 모든 파일을 staging area로..
- git commit -m "Add Index.html"
    - git commit -m "
    <커밋메시지>" => 버전에 대한 이름 표기.. -m은 메시지라는 뜻.

3. git은 파일을 modified, stagted, committed로 관리한다.

