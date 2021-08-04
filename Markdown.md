<h1> 마크다운 특징 </h1>

* 텍스트 기반의 가벼운 마크업 언어

* Github 등 사이트에서는 파일명이 README.md인것을 모두 보여줌

* text to HTML conversion

* 정적사이트 생성기 (기술블로그)

* 개발 환경뿐 아니라, 일반 SW에서도 많이 사용되고 있음

  -----

  <h3>마크다운 문법</h3>

  1. Heading

     - Heading 은 문서의 제목이나 소제목으로 사용

     - 문서의 구조를 위해 작성, 글자크기를 조절하기 위한 용도 XXX
     - #Heading level 1~6

  2. List

     - 순서가 있는 리스트 (ol)  / 순서가 없는 리스트 (ul)

  3. 코드블록 (``` ) 3개

     - 특정언어를 명시하면 syntax highlighting 적용 가능

       ```{first}
       "firstName" : Juhee,
       "lastName" : Park
       ```

  4. 코드블록 (`) 1개

     - inline 

       At the command prompt, type `nano`.

       

  5. 링크 작성 가능 

  [구글](http://google.com)

  6. 이미지 가능 

     ![사진](C:\Users\zoohi\Desktop\768px-HelloWorld.svg.png)

  7. 인용문 가능 (>)

     > When life gives you lemons, make lemonade.

  8. 표 지원

     | syntax | description |
     | ------ | ----------- |
     | Header | Title       |

  9. text 강조 (** , *)

     I **love** you.

     l *like* you.

  10. 3개 이상의 *** / --- / ____ (수직선 사용 가능)

      ----------------------------------------------------------------------

      <h1>버전관리</h1>

      - 동일한 정보에 대한 여러 버전을 관리하는 것

      <h1>Git 기초 흐름</h1>

      - 분산버전 관리 시스템, 코드의 버전을 관리

      - 컴퓨터 파일의 변경사항 추적 / 사용자 간 파일들의 작업을 저율

      - ```{분산버전 관리 시스템(DVCS)
        분산버전 관리 시스템(DVCS) = 원격 저장소
        : 중앙에서 버전 관리하고 클라이언트들이 파일 받아서 사용 
        ```

      - ![기본흐름](C:\Users\zoohi\Desktop\캡처.PNG)

      

  - modified : 파일이 수정된 상태 

  - staged: 수정한 파일을 곧 커밋할 것이라고 표시한상태

  - committed :커밋이 된 상태

    ------------------------------------------------

  ```{
  - CLI (Command Line Interface ) :과거 -> 노력(읽고, 이해)
    1. 명령 2. 결과본다 3. 목록보여줘 (ls = list)
  - GUI (Graphic User Interface) :현재
    1. 오류, 팝업, 변경, 클릭 
  ```

  <기초 CLI 명령어>
  ls : list (목록)
  touch : (파일 만들기)
  pwd : print working directory (현재 작업 디렉토리 출력)
  mkdir test : make directory (디렉토리 만들기)
  cd test : change directory (폴더 이동)

  `

  `..` : 상위 폴더 
  `.` : 현재 디렉토리