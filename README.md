# Readme Formatting
<br/>

<details>
<summary>Text Operations</summary>
<br/>

|Command|Results
|---|---
|#|Big Paragraph + hr
|##|Mid Paragraph + hr
|###|Sml Paragraph
|\<br/>|line space
|\&nbsp;|space
|\~~STRIKE~~ |~~STRIKE~~ 
|\*\*BOLD**|**BOLD**
|\<sup>TEXT\</sup>|<sup>TEXT</sup>
|>quote|quote* <sup>doesn't show</sup>

</details>
<br/>

<details>
<summary>Code</summary>
<br/>


|Command|Results
|---|---
|\`test`|`test`
<br/>


|Command|&nbsp;
|---|---
|\```python<br/> print("text)<br/>\```|↓

```python
print("text")
```
<br/>


|Command|&nbsp;
|---|---
|\```python<br/>require 'redcarpet'<br/>markdown = Redcarpet.new("Hello World!")<br/>puts markdown.to_html<br/><br/>\```|↓

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

</details>
<br/>



<details>
<summary>Media Imports</summary>
<br/>

|Text|On Failed Load|Result
|---|---|---
|\!\[TEXT_IMAGE_NAME]\(FILE_PATH_REPO)|![TEXT_IMAGE_NAME](test2.png)|![TEXT_IMAGE_NAME](test.png)
|\!\[TEXT_IMAGE_NAME]\(URL)| ![TEXT_IMAGE_NAME](test2.png) | ![TEXT_IMAGE_NAME](test.png)
</details>
<br/>



<details>
<summary>Tables and Lists</summary>
<br/>

|Text|Command
|---|---
||Big Paragraph + hr

</details>
<br/>

