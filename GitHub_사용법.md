**## GITHUB 사용법 ## \[ https://www.youtube.com/watch?v=tkkbYCajCjM ] 이해가 안될 시 해당 사이트 ㄱㄱ**



1.New => Create a new repository => Repositoey name에 프로젝트 이름을 넣기 => create repository 클릭



2\. 프로젝트 파일로 선정할 탐색기를 통하여 파일 만들기

ex) 나는 C:\\Python\_Source\\project\_file\\Project\_9 여기에다가 Project\_9라는 파일을 github과 연동



3\. 검색창에서 cmd(명령 프롬토콜)을 열어 위의 예시의 해당 경로로 이동

ex) "cd \\" 입력 후 cd Python\_Source ==> cd project\_file ==> cd Project\_9



4\. 해당 경로로 이동 완료 시 잘 보고 따라할 것

1) git init

2) git clone https://github.com/seongje1/Project\_9.git

   ## 완료 시 master에 있는 파일들이 다 만들어져 있음.

3) Terminal에서 git checkout team\_{숫자} ; 숫자는 1 ~ 4

   # 1: 근호형

  # 2: 근한이형

  # 3: 원경이

  # 4: 성제

4) 해당 branch로 이동 후 각자에 있는 branch에 자신이 한 파일 업로드 추후 develop에 merge 후 master로 올릴예정



**## 파일 올리는 법 ##**

\# 전제조건: 나에게 맞는 branch에 잘 왔는데 확인 한 후 올리기 #

1) git branch  ==> 내가 지금 어디 branch에 있는지 확인 후 맞다면 진행 

2) git status ==> 지금 내 branch에 바뀐게 있는지 확인 하기 \[아마 자기껀 바뀌는게 없을 듯.]

\## git pull origin team\_{숫자} ==> 혹시라도 업데이트 해야할게 있다면, 해당 코드를 쳐서 업데이트

3) git add . / git add {파일이름} ==> "."은 해당 파일을 다 올린다는 의미 / {파일이름}은 해당 파일만 올린다는 의미

4) git status ==> 내가 올릴려는 파일이 잘 올라갔는지 확인

5) git commit -m  "{자기이름}" ==> {자기이름}대신 아무거나 적어도 상관 X

6) git push origin team\_{숫자} ==> 자신에게 맞는 숫자 넣어서 올려주기

7) GITHUB에 들어가서 잘올라갔는지 확인 ==> 끝!!



**## 데이터 병합하기 ##**

1\) MERGE할때는 GITHUB 사이트의 PR(PULL REQUEST)를 사용해서 할 것임.

