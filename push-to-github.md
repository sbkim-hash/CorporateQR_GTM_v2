# GitHub에 올리는 방법

## 1. GitHub에서 저장소 만들기

1. https://github.com/new 접속
2. **Repository name**에 `StoreHub` 입력 (또는 원하는 이름)
3. **Public** 선택
4. **"Add a README file"** 체크 해제 (로컬에 이미 있음)
5. **Create repository** 클릭

## 2. 터미널에서 푸시하기

프로젝트 폴더(`StoreHub`)에서 터미널을 연 뒤, 아래 중 **본인 계정/저장소 이름**에 맞게 고쳐서 실행하세요.

### 이미 원격(origin)이 있을 때

```bash
git remote set-url origin https://github.com/본인아이디/저장소이름.git
git push -u origin main
```

### 원격을 처음 설정할 때

```bash
git remote add origin https://github.com/본인아이디/저장소이름.git
git push -u origin main
```

- `본인아이디`: GitHub 사용자 이름  
- `저장소이름`: 1번에서 만든 저장소 이름 (예: StoreHub)

### 브랜치가 master일 때

```bash
git push -u origin master
```

## 3. 푸시가 안 될 때

- **Repository not found**: GitHub에 해당 이름의 저장소가 있는지, 주소가 맞는지 확인
- **Authentication failed**: GitHub 로그인 필요.  
  - 터미널에서 `git push` 시 사용자명/비밀번호 묻으면, 비밀번호 자리에는 **Personal Access Token** 입력  
  - 토큰 생성: GitHub → Settings → Developer settings → Personal access tokens
