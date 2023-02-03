# 깃 명령어
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
1. 팀폴더 생성
2. git clone 레파지토리경로
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


# head 이동
git checkout develop
git reset -- hard main
git push -f origin develop


