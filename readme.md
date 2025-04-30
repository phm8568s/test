
git init
git add .
git commit -m "git 생성"
git remote add origin 깃허브주소
git branch member
git branch board
git push origin member
git push origin board
집에서
git clone 깃허브주소 .
git switch -c member
파일 만들고( logout.html )
git add .
git commit -m "member logout page"
git push origin member
git switch master
git switch -c board
파일 만들고( delete.html )
git add .
git commit -m "board delete page"
git push origin board