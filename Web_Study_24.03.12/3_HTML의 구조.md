### 기본 HTML 문서 구조

  

HTML 문서의 기본 구조는 뼈대와 같습니다. `<!DOCTYPE html>`으로 문서의 형식을 선언하고, `<html>`, `<head>`, `<body>` 등의 요소를 활용하여 문서의 구조를 정의합니다. 각각의 요소는 시작 태그와 종료 태그로 이루어져 있으며, 이러한 구조를 통해 브라우저는 문서를 올바르게 해석하고 표시할 수 있습니다.

  

### HTML 기본 구조와 요소

  

HTML 문서는 기본적으로 다음과 같은 구조를 갖습니다.

  

```html

<!DOCTYPE html>

<html>

<head>

<meta charset="UTF-8">

<title>문서 제목</title>

</head>

<body>

<!-- 문서 내용 -->

</body>

</html>

```

  

- `<!DOCTYPE html>`: HTML5 문서임을 선언합니다.

- `<html>`: HTML 문서의 시작을 나타냅니다.

- `<head>`: 문서의 메타데이터를 담는 부분입니다. 예를 들면 문서 제목, 문자 인코딩 등을 설정합니다.

- `<meta charset="UTF-8">`: 문서의 문자 인코딩을 UTF-8로 설정합니다.

- `<title>`: 웹 브라우저의 제목 표시줄이나 북마크에서 사용되는 문서의 제목을 정의합니다.

- `<body>`: 실제로 웹 페이지에 표시되는 내용을 담는 부분.

  

### HTML 요소와 태그

  

HTML 문서는 다양한 요소(element)들로 구성되며, 각 요소는 시작 태그와 종료 태그로 이루어집니다.

  

```html

<p>이것은 단락입니다.</p>

```

  

여기서 `<p>`는 시작 태그이고, `</p>`는 종료 태그입니다.

  

### 텍스트 포맷팅

  

HTML은 텍스트를 포맷하는 다양한 태그를 제공합니다.

  

```html

<h1>제목 1</h1>

<p>이것은 단락입니다.</p>

<strong>강조</strong> 또는 <b>강조</b>

<em>이탤릭체</em> 또는 <i>이탤릭체</i>

```

  

### 목록

  

HTML에서 목록을 나타내는데는 `<ul>` (비순서 목록)과 `<ol>` (순서 목록)이 있습니다.

  

```html

<ul>

<li>항목 1</li>

<li>항목 2</li>

<li>항목 3</li>

</ul>

  

<ol>

<li>첫 번째 항목</li>

<li>두 번째 항목</li>

<li>세 번째 항목</li>

</ol>

```

  

### 링크

  

다른 웹 페이지로 이동하거나 파일을 다운로드하는 링크는 `<a>` 태그를 사용합니다.

  

```html

<a href="https://www.example.com">이 링크는 예시 웹사이트로 이동합니다.</a>

```

  

### 이미지 삽입

  

이미지를 웹 페이지에 삽입하려면 `<img>` 태그를 사용합니다.

  

```html

<img src="이미지주소.jpg" alt="이미지 설명">

```

  

### 양식(form)과 입력 요소

  

사용자로부터 정보를 수집하려면 `<form>` 태그를 사용하고, 다양한 입력 요소를 추가할 수 있습니다.

  

```html

<form action="/submit_form" method="post">

<label for="username">사용자명:</label>

<input type="text" id="username" name="username" required>

  

<label for="password">비밀번호:</label>

