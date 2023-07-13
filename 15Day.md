
<h1>15일차</h1>

<h2>ubuntu tomcat에 프로젝트 배포</h2>


</br>
<img width="642" alt="스크린샷 2023-07-14 오전 1 01 03" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/3a0f7a00-e9b9-464a-8fe1-ebee2670d825">
</br>
<h3>ex00 war를 배포 하였다.</h3>
</br>
- scp ex00.war gimduhyeon@우분투 ip:~/Desktop
</br>
- 로컬 -> 우분투 Desktop으로 파일 전송
</br>
- mv 사용해서 톰캣의 webapps밑에 옮김

</br>
<img width="597" alt="스크린샷 2023-07-14 오전 1 01 27" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/7b2f285c-1652-48e6-b587-fc65b6f62818">
</br>
<h3>ex00.war 실행되게 설정.</h3>
</br>
- conf 인가 거기의 server.xml 파일에 Context 부분을 추가하여 내가 배포한 ex00.war 파일을 가르킴
</br>
<h3>실행</h3>
</br>

<img width="587" alt="스크린샷 2023-07-14 오전 1 01 42" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/53866548-c593-400a-a300-806c2045fab6">

</br>
정상적으로 실행된다
