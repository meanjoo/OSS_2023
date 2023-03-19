# OSS_2023

## Git 명령어
* git status  
: 작업 디렉토리(working directory)와 스테이징 영역(staging area)의 상태를 확인하기 위해 사용하는 명령어  

* git add  
: staged 상태로 올려주기 위해 사용하는 명령어  
: git commit을 통해 기록을 남기기 전까지는 아무리 git add를 많이 실행해도 git 레포지토리의 변경 이력에 영향을 미치지 않는다

## Markdown
Markdown 문서 파일의 확장자는 .md이다.

* ### Header 제목
  #으로 시작하는 텍스트이며, #은 1개부터 6개까지 가능하다.  
  #\~######은 HTML의 \<h1>\~\<h6> 태그에 대응된다.  
  #(h1)은 ===로, ##(h2)는 ---로도 만들 수 있다.
  
  ```
  # Header1
  ## Header2
  ### Header3
  #### Header4
  ##### Header5
  ###### Header6
  
  Header1
  ===
  
  Header2
  ---
  ```
  
* ### Emphasis 강조
  * italic 기울여 쓰기
  
    \* 또는 \_를 사용한다. 단, \_를 사용한다면 띄어쓰기에 주의해야 한다.  
    HTML의 \<em> 태그에 대응된다.
    ```
    This is *italic*.
    This is _italic_.
    
    This is*italic*.
    This is_italic_. ← italic 지원 X
    ```
  
  * bold 두껍게 쓰기
  
    \** 또는 \__를 사용한다. italic과 마찬가지로 \__를 사용한다면 띄어쓰기에 주의해야 한다.  
    HTML의 \<strong> 태그에 대응된다.
    ```
    This is **bold**.
    This is __bold__.
    
    This is**bold**.
    This is__bold__. ← bold 지원 X
    ```
  
  * strikethrough 취소선
  
    \~~를 사용한다. HTML의 \<del> 태그에 대응된다.
    ```
    This is ~~strikethrough~~.
    ```
    
* ### List 목록
  * Unordered Lists 순서가 없는 목록
  
    -(hyphen), *(asterisks), +(plus sign)를 이용해서 순서가 없는 목록을 만들 수 있다.  
    기호를 혼용해서 사용해도 된다.  
    들여쓰기를 하면 모양이 바뀐다. ● → □ → ■ (■ 이후로는 계속 ■이다.)  
    HTML의 \<ul> 태그에 대응된다.
    ```
    * Hi
      + Hello
        - World
      * Bye
    ```
  
  * Ordered Lists 순서가 있는 목록
    
    숫자를 써서 순서가 있는 목록을 만들 수 있다.  
    숫자를 무엇을 쓰느냐는 큰 의미가 없고 알아서 순서대로 숫자를 매긴다.  
    (전부 1. 1. 1.을 쓰거나 1. 3. 5.를 써도 1. 2. 3.가 된다.)  
    HTML의 \<ol> 태그에 대응된다.
    ```
    1. First
    2. Second
    3. Third
    ```
    
* ### Check-box 체크 박스
  * 빈 체크 박스
  
    \- [ ]를 통해서 빈 체크 박스를 만들 수 있다.  
    주의할 점은 각 기호 사이에 띄어쓰기가 하나씩 들어가야 한다.  
    - [ ] 빈 체크 박스
    
  * 선택/완료된 체크 박스
  
    \- [x]를 통해서 선택/완료된 체크 박스를 만들 수 있다.  
    [ ] 안의 x는 소문자 x든 대문자 X든 상관없다.  
    - [x] 선택/완료된 체크 박스
