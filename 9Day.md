<h1>생활코딩 리눅스 공부 9일차</h1>

<h2>들어가기 전</h2>

<h3>Super User</h3>

<h3>User 추가 방법은 Google로 그때그때</h3>

</br>

<h2>Super User</h2>

<h3>최고 권력을 가진 사용자</h3>

웬만하면 일반 User로...

</br>

sudo로 일반 user 일 때 super user의 권한을 조금 사용할 수 있음

</br>

ex) sudo apt-get update

</br>

<h2>Super user 로그인</h2>

<img width="569" alt="스크린샷 2023-06-08 오전 1 12 07" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/3e1386f4-f47a-4caa-b13f-3ac04d6058f3">

</br>

su - root :root계정(super user)로 접속해줌

</br>

id : 현재 접속중인 id를 확인하는 명령어

</br>

who : 누가 접속했는지 확인하는 명령어

</br>

처음엔 su - root 를 사용하니 su : sorry 라는 에러 문구가 출력됐음

</br> 

그래서 sudo -s 를 통해 bash-3.2# 에 접속해

</br> 

passwd root 를 입력하여 

</br> 

root계정의 password를 정의해주니 되었음
