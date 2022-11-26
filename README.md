# About Funcoding

- 👋 Hi, I’m @Funcoding
- 👀 I’m interested in UI/UX & Frontend development
- 🌱 I’m currently learning , Javascript Node.js, React.js 
- 💞️ I’m looking to collaborate on my service 
- 📫 Contact us at Email address icodetree@naver.com.

<!---
icodetree/icodetree is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->



# Git 설치
## git-scm.com 에서 다운로드 후 설치  >  vscode 터미널에 git bash 로 변경해야함
## 설치확인
```
git --version
```

## git init 실행하여 저장소 생성
```
git init
git status  -->> git 상태확인
```


## git init 실행하여 저장소 생성
```
git init
git status  -->> git 상태확인
```


## Git 제외파일
## node_module 업데이트 제외  >  .gitignore 파일생성후 제외폴더 작성하면 상태가 히든됨
```
node_modules
```



# github 연결하기

## git name 과 email 등록

```
git config --global user.name 닉네임
git config --global user.email 이메일주소
```

## Github repository 생성하기
## Repository 링크복사 (git clone —> remote add 필요없음!!)
```
git clone 레포지토리 주소
```

## 로컬 폴더 확인 —> .git 폴더 확인
```
git remote add [origin] [깃허브주소]
```

## 중간확인
```
git remote
```

## 파일수정 이후
```
git add .
git status
git commit -m "커밋메세지"
git push origin 브랜치명
```
