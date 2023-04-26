

<h1 id ="Content">Readme Formatting</h1>


Content

[Text_Operations](#Text_Operations)

[Code](#Code)

[Media_Import](#Media_Import)

[Table](#Table)

[List](#List)



<br/>

<h2 id ="Text_Operations">Text Operations</h1>

--- 

|Command|Results*
|---|---
|#|Big Paragraph + hr*
|##|Mid Paragraph + hr*
|###|Sml Paragraph*
|\<br/>|end line*
|\&nbsp;|space
|\~~STRIKE~~ |~~STRIKE~~ 
|\*\*BOLD**|**BOLD**
|\<sup>TEXT\</sup>|<sup>TEXT</sup>
|\[TEXT_LINK_NAME](URL)|[TEXT_LINK_NAME](URL)
|>quote|quote*
  
  
<sup>*no example</sup> <a href='#Content'><sub>dsadsa</sub></a>

<a id="Code"></a>


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
  
````
```diff
- This is a red colored line
+ This is a green colored line
@@ This is a purple colored line @@
```  
````  
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

<sub>[Content](#Content)</sub>



<a id="Media_Import"></a>




|Text|On Failed Load|Result
|---|---|---
|\!\[TEXT_IMAGE_NAME]\(FILE_PATH_REPO)|![TEXT_IMAGE_NAME](test2.png)|![TEXT_IMAGE_NAME](test.png)
|\!\[TEXT_IMAGE_NAME]\(URL)| ![TEXT_IMAGE_NAME](RI3IUEZCJAEPQ) | ![TEXT_IMAGE_NAME](https://raw.githubusercontent.com/l6b7/Git_Formatting/main/404.png?token=GHSAT0AAAAAACB4MTRXSNVPUADD7OMRKPA6ZCJAKQQ)

<sub>[Content](#Content)</sub>

<a id="Table"></a>

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

<sub>[Content](#Content)</sub>

<a id="List"></a>

<table>
<tr>
<td>Syntax</td>
<td>Result</td>
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

<sub>[Content](#Content)</sub>
