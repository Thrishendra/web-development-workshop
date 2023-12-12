# AIM : To Develop HTML and CSS code to display the following content.
![image](https://github.com/SANTHAN-2006/web-development-workshop/assets/80164014/52bf6579-c849-426a-8f40-dc85e874444b)
# Requirements : 
Any code editor(visual studio code) or notepad and any other softwares to run the html file.
# Code:
```html
<!DOCTYPE html>
<html>
  <head>
    <style type="text/css">
      /* Element Selector */
      h1 {
        color: green;
      }

      /* Id Selector */
      #old {
        color: red;
      }

      /* Class Selector */
      .Newcls {
        color: red;
      }

      /* Universal Selector */
      * {
        font-family: 'Times New Roman', Times, serif;
        font-weight: 30%;
      }

      /* Group Selector */
      #col, .oldcls, p2 {
        margin-bottom: 10px;
        color:orange;
      }

      /* Attribute Selector */
      [style="color: blue;"] {
        color: blue;
      }

      /* Pseudo-Class Selector */
      .oldcls > li:first-child {
        color: orange;
      }

      /* Pseudo-Element Selector */
      h2::first-line {
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <h1>Web Development Technologies</h1>
    <h2 id="old">Client Side UI Development</h2>
    <ul id="col">
      <li>HTML</li>
      <li>CSS</li>
      <li>Java Script</li>
      <li>React</li>
      <li>Angular</li>
      <li>Bootstrap</li>
    </ul>
    <h2 class="Newcls">Server Side Development</h2>
    <ul class="oldcls">
      <li>Django</li>
      <li>NodeJs</li>
      <li>Asp.net</li>
      <li>PHP</li>
      <li>Java Spring Framework</li>
    </ul>
    <h2 class="Newcls">Database</h2>
    <ul>
      <li style="color: blue; font-family: 'Times New Roman', Times, serif;" >SQLite</li>
      <li style="color: blue;">MySQL</li>
      <li style="color: blue;">Oracle</li>
      <li style="color: blue;">SQL Server</li>
      <li style="color: blue;">MongoDB</li>
    </ul>
    <h2 class="Newcls">IDE/Editor</h2>
    <ul>
      <li style="color: magenta;">Visual Studio Code</li>
      <li style="color: orange;">Eclipse</li>
      <li style="color: orange;">IntelliJ IDEA</li>
      <li style="color: orange;">Eclipse Theia</li>
    </ul>
    <p5 style="color:brown">Designed by: K. Santhan Kumar</p5>
  </body>
</html>

```
# Output:
![image](https://github.com/SANTHAN-2006/web-development-workshop/assets/80164014/ef51aa09-0072-4e52-b996-6e0204b491e9)
# Result:
The above webpage is designed using all types of selectors in html which also mainly include class selectors,id selectors and tag selectors.
