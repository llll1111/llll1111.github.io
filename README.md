# llll1111.github.io
Chloe's Website.

-

# TODO

- [x] Study Markdown
- [ ] make `index.html`


## Markdown 문법 사용법

### 제목

```html
<h1>heading 1</h1>
<h2>heading 2</h2>
<h3>heading 3</h3>
<h4>heading 4</h4>
<h5>heading 5</h5>
<h6>heading 6</h6>
```

# Markdown H1
## Markdown H2
### Markdown H3
#### Markdown H4
##### Markdown H5
###### Markdown H6

### 목록

```html
<!-- 비순차 목록 -->
ul>li{item$}*3
<ul>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ul>
<!-- 순차 목록 -->
<ol>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ol>
```

### 비순차 목록

- item1
- item2
- item3

### 순차 목록

1. item1
1. item2
1. item3

### 이미지

```html
<img src="http://www.clipartkid.com/images/3/red-rose-clip-art-tattoo-design-just-free-image-download-ToIStL-clipart.jpg" alt="rose">
```
![rose](Assets/rose.jpg "rose")

### 하이퍼링크

```html
<a href="http://iropke.com">이롭게 에이전시</a>
```

- [디자이너에게 영감을 주는 사이트](http://iropke.com/blog/archives/category/project-insight)

### 인용 구문

인용절은 보통 들여쓰기를 통해 사용자에게 일반 문장과 구분해준다<br>
HTML 안에서는 `<blockquote>`요소를 사용하여 인용절을 구조화한다.

> "Design is All. All is Design"<br>
> "Learn By Doing" <br>

### 표

```html	
<table>
	<tr>
		<th>Job Type</th><th>Role</th>
	</tr>
	<tr>
		<th>Job TypePlanner</th><th>Plan</th>
	</tr>
	<tr>
		<th>Designer</th><th>Design</th>
	</tr>
	<tr>
		<th>Developer</th><th>Develop</th>
	</tr>
</table>
```

Job Type | Role
---|---
Planner | Plan
Designer | Design
Developer | Develop