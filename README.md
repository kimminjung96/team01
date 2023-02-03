# 깃 명령어
```
1.원격 팀레파지토리 생성(팀장이 main 브랜치 관리)

2.로컬 레파지토리생성
	git clone 주소
	파일 새로 열기
	git switch -c develop

3.readme.md 파일 만들고 push

main 브랜치 잠금
```
```
echo "# team01" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kimminjung96/team01.git
git push -u origin main
```

# 브랜치전략
팀원 
```
    # 프로젝트 협업 시작하기
1. 팀폴더 생성
2. git clone 경로 => 팀장 레파지토리 내려받기
3. 클론받은 파일을 최상위로 열기 =>안하면 주금
4. 팀원은 git switch -c kmj =>이니셜석자
5. 작업파일 생성
6. git pull origin develop
7. git add .
8. git commit -m "작성내용"
9. git switch develop =>develop브랜치로 변경되었나 확인
10. git merge kmj(내브랜치)
11. git add .
12. git commit -m "230203-kmj-작성내용"
13. git push origin develop
```

# 머지 풀 하기로... 

# head 이동(히스토리가 전부 합병되는 것)
```
git branch main => 로컬에 main이 없으면 생성해줘야 함(있으면 생략)
git checkout develop
git reset -- hard main
git push -f origin main
```

# git 명령어
```
git remote -v => 원격연결 확인

특정 경로지정하려면 git 명령 + origin 경로 적기

git fetch => 깃 코드 내려받기
git merge  => 깃 코드 합치기
git pull => git fetch + git merge 

git pull https://github.com/kimminjung96/test2.git
```

```
git add .
git commit -m "dd"
git switch develop
git merge 내가 한 브랜치
```

홈파일 땡겨오기 
내 브랜치에서 풀 파일 작성하기 
디벨럽 브랜치에가서 머지하고 풀하기 

# main : 서비스 브랜치

# develop: 개발 브랜치

`https://team01.vercel.app/`
