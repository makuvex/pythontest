# pythontest
pythontest

ubuntu git 설치
0. git 설치 후 config 설정하기

sudo apt-get install git-core 

git config --global user.name "이름" 
git config --global user.email "이메일 주소"


1. 내 github에서 repository를 하나 만든다(이미 존재한다면 생성 x)
2. repository의 주소를 복사한다.
3. 내 로컬에 원하는 곳에 git init를 실행한다.
4. git remote add origin "복사한 주소 붙여넣기" 
5. git pull origin master 를 하면 해당 로컬 디렉토리에 repository의 내용을 받아올 수 있다.
6. 이제 원하는 작업을 git add -> git commit -> git push 를 통해 진행 할 수 있다.

참고 사이트
https://yokang90.tistory.com/47
