<h1>생활코딩 리눅스 공부 6일차</h1>

<h2>들어가기 전</h2>

<h3>파일 찾는 명령어들</h3>


</br>

<h2>파일 찾는 명령어</h2>
<h3>locate</h3>

DB(우리가 흔히 아는 DB는 아닌거같음)에서 파일을 찾아줌

</br>

효율성이 좋음

</br>


<h3>find</h3>

파일 디렉토리에서 직접 찾아줌

</br>

<img width="571" alt="스크린샷 2023-06-02 오전 12 34 58" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/be49eabf-d3a3-438e-9a31-487144f9bc8b">

</br>
find ~ -name *.log : 

</br>

<h2>Shell Script</h2>
<h3>명령어의 각본</h3>
<img width="206" alt="스크린샷 2023-05-31 오전 12 13 28" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/1de71cf3-af68-49f3-a53b-3107d7c63241">
</br>
nano backup(스크립트명) 을 이용해 쉘 스크립트 작성
</br></br>
<img width="427" alt="스크린샷 2023-05-31 오전 12 13 47" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/3d78e743-dc51-4f59-a5f3-bf857f354ad3">
</br></br>
<img width="566" alt="스크린샷 2023-05-31 오전 12 14 52" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/2a0a3cd2-e3c5-4e6b-b5a9-26a7cbca9c0e">
</br></br>
chmod +x backup : backup 파일에 x 권한(x는 실행가능한) 명령어를 줌
</br>
ls -l 로 권한 확인 가능


