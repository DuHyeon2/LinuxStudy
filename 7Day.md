<h1>생활코딩 리눅스 공부 7일차</h1>

<h2>들어가기 전</h2>

<h3>Process</h3>

<h3>Background - Foreground</h3>

</br>

<h2>process</h2>

<h3>사용자의 명령어 (mkdir,top,rm) 로 인해 실행되고 있는 상태</h3>

<h3>ps</h3>

현재 실행되는 프로세스를 보여줌

</br>

<img width="578" alt="스크린샷 2023-06-02 오전 12 57 39" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/ec5d844f-e9c2-463b-ab3f-ab5895cbdf55">

</br>

<img width="580" alt="스크린샷 2023-06-03 오후 11 40 26" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/312a59e0-92bd-4d6c-a1ed-879f5080b345">

</br>

<h3>sudo top, htop</h3>

현재 프로세스 리스트를 보여줌

</br>

<img width="573" alt="스크린샷 2023-06-03 오후 11 47 18" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/b7dae189-935f-42c5-89d0-5782e6eeb88c">

</br>

htop 은 다운로드 받아야 해서 그냥 sudo top 만 실행

<h2>background - foreground</h2>

<h3>background</h3>

실행 대기 상태

</br>

<img width="471" alt="스크린샷 2023-06-04 오전 12 36 36" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/0aa0955e-3815-41c8-88b4-2e9e402bba04">

</br>

ctrl + z 가 백그라운드 상태로 종료 시키는건데 맥환경은 안되서 & 를 뒤에 입력함

<h3>foreground</h3>

실행상태

<h3>jobs / kill </h3>

jobs : background-foreground 상태인 리스트 출력

</br>

 -> killㄹ background 상태 애들을 죽일 수 있음 

</br>
 
<img width="410" alt="스크린샷 2023-06-04 오전 12 38 24" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/4695ce1b-0abf-42c9-9dce-e89a6df85e97">





