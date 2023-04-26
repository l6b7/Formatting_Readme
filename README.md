
<h1 id ="Content">Formatting Readme</h1>

<br/>

### Content:

<br/>

<details>
<summary>cheatsheet</summary>
  
<br/>
 
|img | `![TEXT_IMAGE_NAME](test2.png)`
|:--|:--
|set href|`<h3 id ="ID_NAME">NAME</h3>`
|go to href|`<a href='#ID_NAME'><sup>NAME</sup></a>`

  
<table>
<tr>
<td>
Table
</td>
<td>
  
```
|TEXT|TEXT
|---|---
|TEXT|TEXT
```
</td>
</tr>
<tr>
<td>
HTML Table
</td>
<td>

```
<table>
<tr>
<td>TEXT</td>
<td>TEXT2</td>
</tr>
<tr>
<td>TEXT3</td>
<td>TEXT4</td>
</tr>
</table>
```
</td>
</tr>
<tr>
<td>
collapsed 
</td>
<td>
  
```  
<details>
<summary>title</summary>
hidden
</details>
```
</td>
</tr>
</table>    


</details>

<a href='#Text_Operations'>Text Operations</a>

<a href='#Code'>Code</a>

<a href='#Media_Import'>Media Import</a>

<a href='#Table'>Tables</a>

<a href='#List'>Lists</a>

<a href='#Hyperlinks'>Hyperlinks</a>

<br/>

<h2 id ="Text_Operations">Text Operations</h2>

<br/>

|Command|Results
|---|---
|#|Big Paragraph + hr
|##|Mid Paragraph + hr
|###|Sml Paragraph
|\<br/>|end line
|\&nbsp;|space
|\~~STRIKE~~ |~~STRIKE~~ 
|\*\*BOLD**|**BOLD**
|\<sup>TEXT\</sup>|<sup>TEXT</sup>
|\[TEXT_LINK_NAME](URL)|[TEXT_LINK_NAME](URL)
|>quote|quote

<a href='#Content'><sup>Content</sup></a>

<br/>

<h2 id ="Code">Code</h2>

<br/>

<table>
<tr>

<td>Syntax</td>
<td>Result</td>


</tr>
<tr>


<td>`code`</td>
<td>
  
`code`
</td>

</tr>
<tr>


<td>
```python<br/>
print("text)<br/>
```
</td>
  
<td>
  
```python
print("text)
``` 
</td>

</tr>
<tr>

<td>
```ruby<br/>
require 'redcarpet'<br/>
markdown = Redcarpet.new("Hello World!")<br/>
puts markdown.to_html
```
</td>
<td>

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
</td>

</tr>
<tr>

<td>
```diff<br/>
- This is a red colored line<br/>
+ This is a green colored line<br/>
@@ This is a purple colored line @@<br/>
```    
</td>
<td>

```diff
- This is a red colored line
+ This is a green colored line
@@ This is a purple colored line @@
```    
</td>

</tr>
</table>

<a href='#Content'><sup>Content</sup></a>

<br/>

<h2 id ="Media_Import">Media Import</h2>



|Text|On Failed Load|Result
|---|---|---
|\!\[TEXT_IMAGE_NAME]\(FILE_PATH_REPO)|![TEXT_IMAGE_NAME](test2.png)|![TEXT_IMAGE_NAME](test.png)
|\!\[TEXT_IMAGE_NAME]\(URL)| ![TEXT_IMAGE_NAME](BAD_URL.com) | ![TEXT_IMAGE_NAME](https://i.imgur.com/LqshWqB.png)

<a href='#Content'><sup>Content</sup></a>

<br/>

<h2 id ="Table">Tables</h2>


<table>
<tr>
<td>Name</td>
<td>Syntax</td>
<td>Result</td>
</tr>
<tr>
<td>
Basic Table
</td>
<td>
    
```
|TEXT|TEXT
|---|---
|TEXT|TEXT
```
</td>
<td>
    
|TEXT|TEXT
|---|---
|TEXT|TEXT
</td>
</tr>
<tr>
<td>Html Table</td>
<td>

```html
<table>
<tr>
<td>TEXT</td>
<td>TEXT2</td>
</tr>
<tr>
<td>TEXT3</td>
<td>TEXT4</td>
</tr>
</table>  
```

</td>
<td>

<table>
<tr>
<td>TEXT</td>
<td>TEXT2</td>
</tr>
<tr>
<td>TEXT3</td>
<td>TEXT4</td>
</tr>

</table>  

</td>
</tr>
<tr>
<td>HTML Table With Code</td>
<td>

````html
<table>
<tr>
<td>test</td>
<td>test2</td>
</tr>
<tr>
<td>

```
test3
```
</td>
<td>

```
test4
```
</td>
</tr>
</table>  
````
  
</td>
<td>

<table>
<tr>
<td>test</td>
<td>test2</td>
</tr>
<tr>
<td>

```
test3
```
</td>
<td>

```
test4
```
</td>
</tr>
</table>  

</td>
</tr>
</table>

<a href='#Content'><sup>Content</sup></a>

<br/>

<h2 id ="List">Lists</h2>

<table>
<tr>
<td>Syntax</td>
<td>Result</td>
</tr>
  
<tr>
<td>

```
<details>
<summary>title</summary>
hidden
hidden
</details>
```
</td>
<td>

<details>
<summary>title</summary>
hidden
  
hidden
</details>
</td>
</tr>

<tr>
  
<td>
  
`- [x] Completed`
  
`- [ ] Uncompleted`
</td>
<td>
  
- [x] Completed
  
- [ ] Uncompleted
</td>
</tr>
<tr>
<td>
  
`* Item1`
  
`* Item2`
</td>
<td>

* Item1
  
* Item2
</td>
 
</tr>
<tr>
<td>
  
`1. Item1`
  
`2. Item2`
</td>
<td>

1. Item1
  
2. Item2
</td>
 
</tr>
</table> 

<a href='#Content'><sup>Content</sup></a>

<br/>

<h2 id ="Hyperlinks">Hyperlinks</h2>

|set href|`<h3 id ="ID_NAME">NAME</h3>`
|---|:--
|go to href|`<a href='#ID_NAME'><sup>NAME</sup></a>`


<a href='#Content'><sup>Content</sup></a>
