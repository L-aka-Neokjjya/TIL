# Git 자주 사용하는 명령어 정리
자주 사용하는 기본적인 명령어들을 정리하였다.

## 저장소 생성(초기화)하기
```bash
git init # 저장소 생성
```

## 커밋하기
```bash
git add READ.md # 커밋할 파일을 추가
git status # 현재 스테이지 상태 확인
git commit -m "init: README.md" # 인라인 커밋 메시지 작성
git log --decoreate=full --oneline --graph # 커밋 로그 확인
```
* **커밋 메시지** : 작업한 내용의 요약을 적는 것. 나중에 누군가 봤을 때 커밋 메시지만 봐도 어떤 작업을 했는지 알 정도로 신경써서 작성해야 좋다. 좋은 커밋 메시지 작성법은 [여기](https://edykim.com/ko/post/writing-good-commit-messages/)를 참고하자.

## 브랜치 생성하기
```bash
git checkout -b readme # 'readme'라는 이름의 브랜치를 생성한 후, 생성된 브랜치로 체크아웃
```