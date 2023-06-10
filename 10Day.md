<h1>생활코딩 리눅스 공부 10일차</h1>

<h2>들어가기 전</h2>

<h3>User 생성하기 Mac</h3>

<h3>권한 보는법</h3>

<h2>User 생성하기</h2>

<h3>sudo useradd 유저아이디</h3>

이건 기본 unix에서만 통한다

</br>

mac을 사용중인 나는 더 까다롭게 user 생성했음

</br>

<img width="795" alt="스크린샷 2023-06-10 오후 10 49 23" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/349c33dd-dc71-4ab3-ac70-bed27140fd5a">

</br>

sudo dscl 로 각각 id와 shell, unique id,directory, group 등을 만들건 지정해 줬으며

</br>

sudo userpw engus8827로 비밀번호도 설정 해 줬다

</br>

<img width="490" alt="스크린샷 2023-06-10 오후 10 49 46" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/1de7671c-b4b8-4965-a73d-35503ac3ebb2">

</br>

허나 계속 로그인이 안되길래 Users폴더에 id와 같은 폴더인 engus8827을 만들어주니 잘 되었다

<h2>권한 읽는법</h2>

<img width="411" alt="스크린샷 2023-06-10 오후 9 47 10" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/91295864-9bdd-43b3-bb60-9f650fcd8244">

<h3>가장 첫번째 -</h3>

파일의 타입

<h3>rwe</h3>

아래 세글자로 끊어 읽으면 된다
</br>
r : read
</br>
w : write
</br>
e : execute
</br>
- : 여기에 위치한 권한의 권한 없음
</br>
처음은 owner의 권한 (gimduhyeon)
</br>
두번짼 group의 권한 (staff)
</br>
세번짼 모두의 권한
</br>
마지막은 날짜와 파일의 이름으로 구성되어 있다
