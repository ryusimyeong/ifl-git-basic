# github

원격저장소를 만들 수 있는 개발자들의 커뮤니티

원격저장소 ? 인터넷 세상 어딘가 있는 저장소

파일 만들기

git init

git add file.name

git commit -m "commit message"

git remote add origin url


tip: add 와 commit 을 한 번에 하기 (단, 한 번이라도 commit을 한 파일에만 가능)

```
git commit -am "commit message"
```


github에 push 하기

git remote add origin url -> url에 있는 원격저장소에 내 로컬 저장소를 연결

git push -u origin master -> 내 코드를 push하는 명령어

