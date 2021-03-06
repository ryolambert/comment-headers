<h1 align="center">
  <br>
  <a href=""><img src="images/icon.png" alt="icon" width="150"></a> 
</br>
</br>
COMMENT HEADERS
</br>
</br>

<!-- [![Installs](https://vsmarketplacebadge.apphb.com/downloads/akmarnafi.comment-headers.svg)](https://marketplace.visualstudio.com/items?itemName=akmarnafi.comment-headers)
[![Version](https://vsmarketplacebadge.apphb.com/version/akmarnafi.comment-headers.svg)](https://marketplace.visualstudio.com/items?itemName=akmarnafi.comment-headers)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/akmarnafi.comment-headers.svg)](https://marketplace.visualstudio.com/items?itemName=akmarnafi.comment-headers) -->

</h1>

<p align="center">
  <a href="#how-to-use">How To Use</a> •
  <a href="#types">Types</a> •
  <a href="#line-style">Line styles</a> •
  <a href="#supported-languages">Supported languages</a> 
</p>



<br>
<div align="center">
<h3></underline>Write beautifully structured code &#127881;</h3>
<h4 align="center"><a href="#supported-languages">Supports 30+ languages</a></h4>
<h4 align="center">Works with <a  href="vscode:extension/aaron-bond.better-comments">Better comments</a></h4>
</br>
<img  src="images/banner.png" alt="screenshot" width="900" >

</div>



<div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;</div>



<br>


## How to use

Type a trigger keyword like `//header-lg` and press enter.<br>
Find the different triggers in the types section.

<img src="images/howto.gif" alt="multiline" width="800" >
<br>
<br>
<div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;</div>
<br>


## Types

### 1. Block

| Type     | Identifier                   | Example                                 |
| -------- | ---------------------------- | --------------------------------------- |
| Default  | `block`                      | `//block-md`..                          |
| Info     | `info-block` ,`*block`       | `//info-block-md`, `//*block-md`..      |
| Question | `question-block`,`?block`    | `//question-block-md` , `//?block-md`.. |
| Warning  | `warning-block`,`!block`     | `//warning-block-md`, `//!block-md`..   |
| Todo     | `todo-block`                 | `//todo-block-md`..                     |
| Function | `function-block`             | `//function-block-md`,.. 
| About    | `about-block`                | `//about-block-md`..                    |

<br>
<img src="images/blocks.png" alt="block" width="600" >

<br>

### 2. Header

| Type     | Identifier                   | Example                                   |
| -------- | ---------------------------- | ----------------------------------------- |
| Default  | `header`                     | `//header-md`..                           |
| Info     | `info-header` , `*header`    | `//info-header-md`, `//*header-md`..      |
| Question | `question-header`, `?header` | `//question-header-md` , `//?header-md`.. |
| Warning  | `warning-header`, `!header`  | `//warning-header-md`, `//!header-md`..   |
| Todo     | `todo-header`                | `//todo-header-md`..                      |

<br>
<img src="images/headers.png" alt="header" width="700" >

<br>

### 3. Footer

| Type    | Identifier | Example                   |
| ------- | ---------- | ------------------------- |
| Default | `end`      | `//end-sm`, `//end-md` .. |

<br>
<img src="images/footers.png" alt="footer" width="900" >
<br>

### 4. Divider

| Type    | Identifier | Example                           |
| ------- | ---------- | --------------------------------- |
| Default | `divider`  | `//divider-sm`, `//divider-md` .. |

<br>
<img src="images/dividers.png" alt="dividers" width="900" >
<br>

### 5. Divider plain

| Type    | Identifier      | Example                                       |
| ------- | --------------- | --------------------------------------------- |
| Default | `divider-plain` | `//divider-plain-sm`, `//divider-plain-md` .. |

<br>
<img src="images/dividers-plain.png" alt="dividers plain" width="900" >
<br>

### 6. Inline

| Type     | Identifier      | Example              |
| -------- | --------------- | -------------------- |
| Default  | `comment`       | `//comment`          |
| Info     | `info` , `*`    | `//info`, `//*`      |
| Question | `question`, `?` | `//question` , `//?` |
| Warning  | `warning`, `!`  | `//warning`, `//!`   |
| Todo     | `todo`          | `//todo`             |

<br>
<img src="images/inline.png" alt="inline" width="600" >
<br>

### 7. Multiline

| Type    | Identifier  | Example       |
| ------- | ----------- | ------------- |
| Default | `multiline` | `//multiline` |

<br>
<img src="images/multiline.png" alt="multiline" width="600" >
<br>
<div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;</div>
<br>

## Line Style

| Type         | Identifier | Example       |
| ------------ | --------- | ------------- |
| Single lined | `/`       | `/header-sm`  |
| Double lined | `//`      | `//header-sm` |

<h4>Single lined</h4>
<img src="images/single-line.png" alt="single line" width="600" >

<h4>Double lined</h4>
<img src="images/double-line.png" alt="double line" width="600" >

<br>
<div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;</div>
<br>

## Sizes

| Type              | Identifier | Example        |
| ----------------- | ---------- | -------------- |
| Small             | `-sm `     | `//header-sm`  |
| Medium            | `-md `     | `//header-md`  |
| Large             | `-lg `     | `//header-lg`  |
| Extra Large       | `-xl `     | `//header-xl`  |
| Extra Extra Large | `-xxl `    | `//header-xxl` |

Note: Inline(6) and Multiline (7) comments do not have size option.

<br>

<div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;</div>
<br>

## Supported Languages

<details>
<summary>(expand)</summary>

-    C
-    C#
-    C++
-    Coffeescript
-    Coldfusion\*
-    CSS
-    Dart
-    Dockerfile
-    Go
-    Groovy
-    HTML\*
-    Java
-    Javascript
-    JOSC
-    LESS
-    Markdown\*
-    Nested
-    Nim
-    Objective-c
-    Objective-cpp
-    Perl
-    Php
-    Powershell
-    Puppet
-    Python
-    R
-    Ruby
-    Rust
-    SASS
-    SCSS
-    Shellscript
-    SQL
-    Stylus
-    Swift
-    TCL
-    Typescript
-    Vue
-    XML\*
-    XSL\*
-    YAML
     <br> \*supports only dividers

</details>
<br>

<!-- <div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;</div> -->
<div align="center">&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;&#12336;
</div>
<br>
<div align="center">Happy Coding <img src="images/trollface.png" height="20"></div>
