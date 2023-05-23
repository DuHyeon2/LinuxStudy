<h1>생활코딩 리눅스 공부 4일차</h1>

<h2>들어가기 전</h2>
input/output에 대해 배웠지만 중요하 부분은 아닌거같음

</br>

하나의 input 두개의 output


<h2>output</h2>
<h3>명령을 출력 해 주는 기능</h3>

<h3>output 예제</h3>
> : 가장 기본적인 output(standard output)

</br>

<img width="572" alt="스크린샷 2023-05-24 오전 12 27 08" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/516c34c1-329d-4a84-92f8-e20894c67597">

</br>

ls -l 의 결과값을 result.txt에 저장함

</br>

<h3>error output 예제</h3>

1> : standard output(가장 기본적인 output)
2> : error output(에러 output)

</br>

<img width="488" alt="스크린샷 2023-05-24 오전 12 32 44" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/c2ca0d8e-71bb-45de-868f-357ae9038e04">

</br>

에러 로그가 error.log에 저장되는것을 볼 수 있다.

</br>

<h3>car 예제</h3>
cat :  화면을 출력 해 줌(원래는 여러개의 인자를 결합해주는것)

</br>

사용자가 키보드로 입력한 정보를 standard input으로 받음

</br>

<img width="364" alt="스크린샷 2023-05-24 오전 12 39 28" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/3db4790f-c0aa-49b8-b0a1-8707cdf4a1b4">

</br>


<h2>input</h2>

<h3>인자가 아닌 표준 입력(별로 실용적이지 않음)</h3>

<h3>input 예제</h3>

<img width="553" alt="스크린샷 2023-05-24 오전 12 40 53" src="https://github.com/DuHyeon2/LinuxStudy/assets/83499405/261b94ce-9f8a-4379-bdb4-903e44bf780e">

</br>

< : input 명령어

</br>

cat :  화면을 출력 해 줌(원래는 여러개의 인자를 결합해주는것)

</br>

head : 인자의 10줄을 출력해줌

</br>

-n1 : 인자의 첫줄만 출력해줌(head와 같이 사용

</br>

>> : append -> 값을 더한다 
