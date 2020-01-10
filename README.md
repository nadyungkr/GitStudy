## Study-git
===

#은 5개까지 사용 가능

1개 = 가장 크다
5개 = 가장 작다

소스코드 블록은 숫자키 1옆에 `로 작성


````
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <style>
    *{margin:0; padding:0;}
    h1{font-size:24px;}
    p{color:#f0f;}
  </style>
  <title>Document</title>
</head>
<body>
   <h1>hello</h1>
   <p>Today, Im going to study git.</p>
</body>
</html>
````

링크는 다음과 같이 작성
[대괄호에는] 링크이름 적기
(소괄호에는) 링크적기
cf. 대괄호와 소괄호 사이에 공백은 주소가 걸어지지 않습니다.

[링크이름](https://github.com/nadyungkr)


순서 없는 목록은 다음과 같이 작성할 수 있습니다

* 나듕 git repository
  * portpolio
  * js study
  * git study
  * clone coding
    * html
    * css
    * js
    * jquery
    * react
    
 자주 사용하는 인용구문은 다음과 같이 작성할 수 있습니다
 
 > '성실하다의 반대말은 미래에 대한 포기이다.' - 나듕이 -
 
 테이블은 다음과 같이 작성할 수 있습니다.
 
 종류|예시|예시2|예시3
 |---|---|---|---|
 식물|씨앗|잎사귀|줄기
 나라|한국|미국|캐나다
 
 강조는 다음과 같이 작성할 수 있습니다
 **강조** ~~취소~~
 
 
 ### 깃 사용법 Repository clone 하기
---

1. New Repository

2. 원격저장소(github)와 연결할 로컬저장소의 폴더를 만든다. (ex. c\repository)

3. 터미널을 연다. (파워셀, vscode 터미널 등등) c\repo로 이동해서 프로젝트(레포지토리)를 clone한다.  
<code>git clone 프로젝트 깃 주소</code>

4. c\repo 오류가 없이 실행되었다면 repo 폴더에 repository 폴더가 생성된다.

5. 생성된 폴더안에 소스파일들을 만들어준다.

### 원격 저장소로 보내는 방법
---

1. 터미널을 실행하여 로컬 주소를 확인한 후 로컬저장소 폴더의 주소를 입력한다. 예) cd repo

2. <code>git add . </code>  
해당 프로젝트 폴더의 **모든 파일들을** 스테이지에 올린다.

3. <code>git commit -m "커밋할 내용" </code>  
push하기전 **어떤 내용을 작업했는지 메모**하는 작업

4. <code>git push </code>  
스테이지에 있는 파일들을 원격저장소로 push한다.

5. 2~3 번의 기능은 <code>git commit -am "커밋할 내용"</code> 으로 축약해서 쓸 수 있다.


### 파워쉘 명령어
---

*명령어
  *<code>cd..    </code>          //상위폴더로 이동
  *<code>cd. \하위폴더이름 </code>   //하위폴더로 이동
  *<code>cd 로컬주소   </code>     //해당폴더로 이동

