# CLI 기초

## CLI 개념
- 터미널을 통해 사용자와 컴퓨터가 상호 작용하는 방식

## 터미널 명령어
1. `touch` : 파일을 생성하는 명령어
2. `mkdir` : 새 폴더를 작성하는 명령어
3. `ls` : 현재 작업 중인 디렉토리의 폴더와 파일을 보여 주는 명령어
4. `mv`
    - 파일을 폴더 안에 옮길 때 사용하는 명령어
    - 폴더 이름이 존재하지 않는다면 파일 이름을 바꿔 주는 명령어
5. `cd` : 작업 중인 디렉토리를 변경해 주는 명령어
6. `rm` : 폴더 및 파일을 지우는 명령어
    - 폴더를 지울 때는 `rm -r` 사용

## 유용한 단축키
1. `tab` : 폴더/파일 이름 자동 완성
2. `ctrl+l` : 터미널 화면을 청소해 주는 단축키 (휴지통은 아님)

# git 기초

## git 초기 설정
- `git config --global user.name "이름"`
- `git config --global user.email "갓허브 가입한 이메일 주소"`
- `git config --global core.editor "code --wait"`
- `git config --global --list`

## git 프로세스
1. `git init`로 git 시작
2. `git status`로 git의 상태 확인 가능
3. `git add`로 working directory 상태에 있는 내용을 staging area로 올려 줌
4. `git commit -m "메시지"` : staging area에 있는 내용을 커밋(버전)으로 저장하는 명령어
    - `git log`의 경우 커밋의 내용을 조회할 수 있는 명령어
    - `git log --oneline` 한줄로 코드를 보여 주는 명령어

## 로컬 저장소를 원격 저장소에 등록, 조회, 삭제하는 법
1. 원격 저장소 등록 : `git remote add <이름> <주소>`
    - ex) `git remote add origin https://`
2. 원격 저장소 조회 : `git remote -v`
3. 원격 저장소 연결 삭제 : `git remote remove <이름>`


