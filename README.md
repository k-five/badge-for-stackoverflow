<h1>badge-for-stackoverflow</h1>

<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23F80.svg" />

<h1>Hi</h1>

During developing my app (= <a href="https://github.com/k-five/badge-for-git" >badge-for-git</a>) I realized that I can use these badges (= SVG files) on <a href="">my stack-overflow profile</a>  
So here is a guide for you that you can use it as well.  

<h3>What you need:</h3>  

 1. an account on **github.com** (for storing the SVG files)  
 2. create a repository (short name is preferable, mine is <a href="https://github.com/k-five/s">s</a>)  
 3. use <a href="https://github.com/k-five/badge-for-git" >badge-for-git</a> and create what you want  
 4. follow the instructions I putted there (= on badge-for-git, step 1 through 6)  
 5. then follow the below steps  


<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23E1.svg" />

<h3>step.1 click on your own SVG-file</h3>  

<img src="bfs.1.png" />

<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23E1.svg" />

<h3>step.2 click on "Raw" button</h3>

<img src="bfs.2.png" />

<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23E1.svg" />

<h3>step.3 see the source-code and notice to the "url"</h3>

<img src="bfs.3.png" />

It consists of:  

 1. `https://`  
 2. `raw.`  
 3. `github`, `user`, `content` and `.com`. altogether: `githubusercontent.com`  
 4. your user-name, mine is `k-five`  
 5. your repository name, mine is `s`  
 6. branch, mine is `master`  
 7. directory name, mine is `a`  
 8. name of the SVG file, mine is `bpy-bfg.svg`  

<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23E1.svg" />

<h3>step.4  add suffix to the url</h3>

<img src="bfs.4.png" />

 1. suffix: `?sanitize=true`
 2. press **Enter**
 3. if want to see a clean source-code, right-click add see: "view-source-page" (optional)
 4. copy the URL

<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23E1.svg" />

<h3>step.5 </h3>

go on your **stack-overflow** account on anywhere you like use an `img` HTML tag or use stack-overflow shortcut: `![file-name](file-URL)`


<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23F80.svg" />


<h3>Example 1. img tag</h3>

for me:  `<img src="https://raw.githubusercontent.com/k-five/s/master/a/pby-bfg.svg?sanitize=true" />`

<h3>Example 2. shortcut</h3>

for me:  `![powered-by-badge-for-git](https://raw.githubusercontent.com/k-five/s/master/a/pby-bfg.svg?sanitize=true)`  

<h3>Tip. add link to it</h3>

by default if you add with an `<img>` tag or even `![]()` shortcut you cannot click on and the SVG file refers to **nowhere**  
So if you want to add a link to it:

for me:  
```html
<a href="https://github.com/k-five/badge-for-git">
  <img src="https://raw.githubusercontent.com/k-five/s/master/a/pby-bfg.svg?sanitize=true" />
</a>
```

with shortcut:  
```
[![](https://raw.githubusercontent.com/k-five/s/master/a/pby-bfg.svg?sanitize=true)]
(https://github.com/k-five/badge-for-git)
```


<h3>result</h3>
<a href="https://stackoverflow.com/users/4643584/shakiba-moshiri?tab=profile">My Profile on Stack-Overflow</a>

<h1>if</h1>

 1. you have any questions, ideas, problems, etc raise an issue on <a href="https://github.com/k-five/badge-for-git" >badge-for-git</a>
 2. you are curious about what **sanitize** does see <a href="https://www.w3schools.com/php/php_filter.asp">w3schools.com</a>

<img src="https://github.com/k-five/badge-for-git/blob/master/res/line/line5-900px-%23E1.svg" />

<h1>troubleshooting</h1>

 - if you did not get the correct result, make user the **URL** is valid and correct, the `?sanitize=true` is vital!  
 - if you changed a file (= SVG) or wanted to replace it, it is better to clean you **cache** otherwise may do do not get the result  
