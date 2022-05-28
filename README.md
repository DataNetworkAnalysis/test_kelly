# test_kelly
test repo
[github 협업 명령어 총정리](https://velog.io/@tami/git-hub-%EB%A1%9C-pull-request-%ED%95%98%EB%8A%94-%EB%B2%95) <br>

# 1. 시작 전 (완전 처음일 때)에 충돌방지를 위해 각자의 branch를 생성 해줍니다. <br>

코드로 하는 브랜치 생성 방법은 다음과 같습니다. <br>
VS Code의 터미널에서
```
git branch 브랜치네임   # 브랜치 생성
git checkout 브랜치네임 # 브랜치로 이동
```
을 입력하여 생성하거나... github의 repo 페이지에서 생성이 가능하다면 거기서 생성... <br>
<br>

branch 바꾸는 박스를 눌러서 (find or create a branch가 적혀있는) 입력박스에 원하는 브랜치 네임을 입력 후 아래 생긴 create 버튼을 누름으로써 새로운 브랜치를 생성한다. <br>
[참고](https://redcow77.tistory.com/438) <br>
<br>

# 2. 작업 시작 전에는 무조건 pull을 해서 최신 소스를 불러와야한다.

```
git pull
```
해당 작업을 하지않으면 작업간 충돌이 발생할 수 있다.