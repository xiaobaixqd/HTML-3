# HTML常用标签

* <strong>a标签的用法</strong>
    1. a的href的取值 <br>
       网址：https://google.com, http://google.com, //google.com <br>
       路径：a/b/c 以及 /a/b/c,  index.html或./index.html <br>
       <pre> 伪协议: JavaScript:代码; <br> 
                mailto:邮箱，tel:手机号，id，href=#xxx </pre>
    2. a标签的作用 <br>
       跳转外部页面 <br>
       跳转内部锚点 <br>
       跳转到邮箱或电话 <br>
     <br>
* <strong>img标签的用法</strong> <br><br> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. 作用：发出get请求，展示一张图片 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. 属性：alt/height/width/src

* <strong>table标签的用法</strong><br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. thead tbody tfoot<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tr(table row) 表格中的一行，th 表头，td(table data) 数据<br>
例：<br>
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <table>
      <thead>
        <tr>
          <th></th>
          <th>小红</th>
          <th>小明</th>
          <th>小颖</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>数学</th>
          <td>61</td>
          <td>91</td>
          <td>85</td>
        </tr>
        <tr>
          <th>语文</th>
          <td>79</td>
          <td>82</td>
          <td>92</td>
        </tr>
        <tr>
          <th>英语</th>
          <td>100</td>
          <td>97</td>
          <td>87</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <th>总分</th>
          <td>200</td>
          <td>200</td>
          <td>200</td>
        </tr>
      </tfoot>
    </table>
  </body>
</html>
```

* <strong>其他感想</strong><br>
   我觉得html知识点比较细，琐碎，要想学好，要多复习，多练，多尝试代码，才能更好得掌握，学前端还任重而道远啊，加油！！！
