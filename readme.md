# git 버전관리 기초

git init : 로컬 저장소 생성

1. Working Directory(작업한 파일 상태) -> `git add` -> Staging Area(커밋할 파일 상태 목록) -> `git commit` -> Repository
2. 사용자 설정
    - git config --global user.email "email"
    - git config --global user.name "name"

예시
- git add index.html => staging area에 추가히기 위해 사용. 
    - untracked 상태의 파일을 staged로 변경
    - modified 상태의 파일을 staged로 변경
    - git add . => 현재 경로의 모든 파일을 staging area로..
- git commit -m "Add Index.html"
    - git commit -m "
    <커밋메시지>" => 버전에 대한 이름 표기.. -m은 메시지라는 뜻.

3. git은 파일을 modified, stagted, committed로 관리한다.

---

1. 상태보기 
    - git status (woring directory, staging area) => git 저장소에 있는 파일의 상태를 확인하기 위하여 활용.
    - git log (repository)
        - git log -1
        - git log --oneline
        - git log -2 --oneline

---

# git에 올리기
1. git remote add origin https://github.com/Imshyeon/django1.git
2. git push origin main