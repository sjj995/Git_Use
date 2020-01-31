Git MarkDown 사용법
===================

## 1. 마크다운 언어란?

마크다운(markdown)은 일반 텍스트 문서의 양식을 편집하는 문법이다. README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쓰인다. 마크다운을 이용해 작성된 문서는 쉽게 HTML 등 다른 문서형태로 변환이 가능하다.
존 그루버에 의해 만들어졌으며, 사람들이 읽기 쉽고 쓰기 쉬운 플레인 텍스트 포맷을 사용하여 쓸 수 있으면서 구조적으로 유효한 XHTML(또는 HTML)로 선택적 변환이 가능하게 하는 것이 목표이다.   
출처 : [wikipedia](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)


## 2. 마크다운 언어 사용법

### 2.1 Headers
* 헤더 크기 : '#' 문자를 사용해서 크기를 조정한다.  
'#' 문자가 한 개부터 시작해서 여섯 개까지 설정 가능하며, 한 개일때가 가장 큰 경우이다.
# 헤더 크기 (h1)
## 헤더 크기 (h2)
### 헤더 크기 (h3)
#### 헤더 크기 (h4)
##### 헤더 크기 (h5)
###### 헤더 크기 (h6)

### 2.2 목록
##### 2.1.1 번호 없는 목록 만들기 : '*','+','-', 사용해서 목록을 만들 수 있다.

* title 1
   * title 1.1
   * title 1.2
* title 2
  
+ 제목 1
  + 제목 2
    + 제목 3
  
- 이런식으로 이용이 가능하며 들여쓰기를 할 경우, 들여쓰기가 그대로 적용된 것을 확인 할 수 있다.(들여쓰기는 tab 두 번)

##### 2.1.2 번호 있는 목록 만들기

* 번호는 '*'와 같은 기호 대신에 '1.' 을 사용해주면 된다. (들여쓰기는 동일하게)

1. title 1
1. title 2
1. title 3
    1. title 3.1
    1. title 3.2


### 2.3 개행

- 개행 같은 경우에는 space bar 두 번이상 누르고 다음 줄에 작성을 해주게 되면 강제 개행을 할 수 있다.

### 2.4 링크

* [링크](링크할 주소) 이런 식으로 입력해주면 링크가 가능하다

[승재의 깃허브](https://github.com/sjj995/)

### 2.5 이미지 삽입

* 이미지를 삽입하기 위해서는 이미지가 있어야된다.  
* 당연한 말이지만, 따라서 깃허브 데스크탑으로 연동을 시키든, 링크가 필요하다.

#### 방법

<pre><code>Format : ![이미지 삽입방법](/images/이미지저장방법.JPG)</code></pre>









