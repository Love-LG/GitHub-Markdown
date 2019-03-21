# GitHub-Markdown
GitHub常用的markdown语法

### 1.markdown常用列表
无序列表使用`*`语法如下：
```bash
* item1
* item2
* item3
  * item3_1
  * item3_2
* item4
```
<details>
  <summary>Example</summary>
  
  * item1
  * item2
  * item3
    * item3_1
    * item3_2
  * item4
  
  </details>
  
  <br>[⬆ Back to top](#contents)
  
  有序列表的使用语法如下：
  ```bash
  1. item1
  2. item2
  3. item3
     1. item3_1
     2. item3_2
  4. item4
  ```
  <details>
 <summary>Example</summary>
 
 1. item1
 2. item2
 3. item3
    1. item3_1
    2. item3_2
 4. item4
 
 </details>
 任务列表使用`- []`语法：
 
 ```bash
 - [x] Create a repo
 - [ ] pull a requst
 - [ ] push a commit
 ```
 <details>
 <summary>Example</summary>
 
 - [x] Create a repo
 - [ ] pull a request
 - [ ] push a commit
 
 </details>
 
 <br>[⬆ Back to top](#contents)

### 2.markdown标题
markdown常用标题使用`#`语法如下：
```bash
# this is <h1> tag
## this is <h2> tag
### this is <h3> tag
###### this is <h6> tag
```
<details>
 <summary>Example</summary>
 
# 这是一级标题
## 这是二级标题
### 这是三级标题
 
 </details>
 
  <br>[⬆ Back to top](#contents)
  ### 3.markdown链接与图片
  markdown插入链接使用`[描述](url)`插入图片使用`![描述](url)`语法如下：
  ```bash
  [baidu](https://www.baidu.com)  //插入链接
  ![tomcat](https://octodex.github.com/images/yaktocat.png)  //插入图片
  ```
  <details>
 <summary>Example</summary>
 
 [baidu](https://www.baidu.com)
 
 ![yackocat](https://octodex.github.com/images/yaktocat.png)
 
 </details>
 
 <br>[⬆ Back to top](#contents)
 
### 4.markdown表格
```bash
first Header | second Header
------------ | -------------
this is paat1 | this is part2
this is part3 | this is part 4
```
<details>
 <summary>Example</summary>
 
 first Header | second Header
------------ | -------------
this is paat1 | this is part2
this is part3 | this is part 4

 </details>
 
<br>[⬆ Back to top](#contents)

### 5.使用emoji
github使用emoji的语法为 `:emojicode:`更多的emoji图标[emojicode](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
```bash
today am so happy :smile:

this is good! :+1:
```
<details>
 <summary>Example</summary>
 
today am so happy :smile:

this is good! :+1:

 </details>
 
<br>[⬆ Back to top](#contents)
### 6.键盘按钮
键盘按钮的语法为`<kbd><kbd>`
```bash
<kbd>Ctrl</kbd><kbd>C</kbd>
```
<details>
 <summary>Example</summary>
 copy is:
 <kbd>Ctrl</kbd>+<kbd>C</kbd>
 </details>

<br>[⬆ Back to top](#contents)

### 7.图片与链接结合
```bash
[![License](https://img.shields.io/badge/license-CC0--1.0-blue.svg)](https://github.com/30-seconds/30-seconds-of-code/blob/master/LICENSE) 
[![npm Downloads](https://img.shields.io/npm/dt/30-seconds-of-code.svg)](https://www.npmjs.com/package/30-seconds-of-code)
```
<details>
 <summary>Example</summary>
 
 [![License](https://img.shields.io/badge/license-CC0--1.0-blue.svg)](https://github.com/30-seconds/30-seconds-of-code/blob/master/LICENSE) 
 [![npm Downloads](https://img.shields.io/npm/dt/30-seconds-of-code.svg)](https://www.npmjs.com/package/30-seconds-of-code)
 
 </details>

### 插入代码
```bash
插入普通代码用：
```bash
```

插入js代码
```js

```

插入css代码
```css
css代码
```

插入HTML代码
```html
html代码
```
其他类似
```
