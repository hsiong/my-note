# This is a brief introduction about MarkDown .  

- [1. 标题](#1-标题)
- [&num; 标题1](#-标题1)
  - [&num;&num; 标题2](#-标题2)
    - [&num;&num;&num; 标题3](#-标题3)
- [2. 换行](#2-换行)
- [3. 粗斜体](#3-粗斜体)
- [4. 线](#4-线)
  - [4.1 分隔线](#41-分隔线)
  - [4.2 删除线](#42-删除线)
  - [4.3 下划线](#43-下划线)
  - [4.4 脚注](#44-脚注)
- [5. 段落标记](#5-段落标记)
  - [5.1 列表](#51-列表)
  - [5.2  列表嵌套](#52--列表嵌套)
- [6. 区块](#6-区块)
  - [6.1 区块引用](#61-区块引用)
  - [6.2 区块中使用列表](#62-区块中使用列表)
  - [6.3 列表中使用区块](#63-列表中使用区块)
- [7. 代码](#7-代码)
- [8. 链接](#8-链接)
  - [8.2 高级链接(不常用, 可不记)](#82-高级链接不常用-可不记)
- [9. 图片](#9-图片)
  - [9.1 常用方案](#91-常用方案)
  - [9.2 替换方案(可不记)](#92-替换方案可不记)
- [10. 表格](#10-表格)
- [10.1 语法格式](#101-语法格式)
  - [10.2 设置对齐](#102-设置对齐)
- [11. 高级技巧](#11-高级技巧)
  - [11.1 锚点](#111-锚点)
  - [11.2 vscode-markdown实时预览](#112-vscode-markdown实时预览)
  - [11.3 html](#113-html)
  - [11.4 转义](#114-转义)
    - [11.4.1 使用转义字符](#1141-使用转义字符)
    - [11.4.2 使用html转义字符](#1142-使用html转义字符)
  - [11.5 公式](#115-公式)
  - [11.6 流程图](#116-流程图)

# 1. 标题 
# &num; 标题1   
## &num;&num; 标题2 
### &num;&num;&num; 标题3 
...

# 2. 换行  
![image](https://user-images.githubusercontent.com/37357447/148874925-1b6c44c0-0e36-4e84-b203-ffeedbca97ea.png)
![image](https://user-images.githubusercontent.com/37357447/148875011-c76f9415-e4fa-419b-9673-dac3f3275aa0.png)


# 3. 粗斜体  
&ast;斜体&ast; *斜体*  
&ast;&ast;粗体&ast;&ast; **粗体**  
&ast;&ast;&ast;粗斜体&ast;&ast;&ast; ***粗斜体***  

# 4. 线  
## 4.1 分隔线   
&ast;&ast;&ast; ***  
## 4.2 删除线  
&bsim;&bsim;波浪&bsim;&bsim;波浪 ~~波浪波浪波浪波浪波浪~~波浪  
## 4.3 下划线
&lt;u&gt;下划线&lt;/u&gt; <u>下划线</u> 
## 4.4 脚注
使用脚注 &lsqb;^footnote&rsqb;  
创建脚注 &lsqb;^footnote&rsqb; : I'm Jf  
使用脚注[^footnote]  
[^footnote]: I'm Jf    

# 5. 段落标记
## 5.1 列表
* 第一项  &ast; 第一项 
+ 第二项  &plus; 第二项  
- 第三项  &boxh; 第三项  
## 5.2  列表嵌套
![image](https://user-images.githubusercontent.com/37357447/148867730-ba2c2c95-1162-4857-9730-5cdd784fd60f.png)
1. 第一列表
    + 第一项
    + 第二项
3. 第二列表
    + 第一项
    + 第二项

# 6. 区块
## 6.1 区块引用
&gt; 区块引用  
&gt;&gt; 第一层  
&gt;&gt;&gt; 第二层  
> 区块引用
> > 第一层
> > > 第二层
## 6.2 区块中使用列表
![image](https://user-images.githubusercontent.com/37357447/148867429-93ba161b-c5c4-416a-b2fd-26d6bae15c3a.png)
> 区块中使用列表
> 1. 列表1
> 2. 列表2
> + 第一项
> + 第二项
## 6.3 列表中使用区块
![image](https://user-images.githubusercontent.com/37357447/148869958-1cabf8ae-c0f1-42fa-bd6d-6e2b9c6bb425.png)
+ 第一列表
    > 第一区块
    > > 第二区块  
+ 第二列表

# 7. 代码
![image](https://user-images.githubusercontent.com/37357447/148870199-6b7be645-41d2-4647-8776-2157cb78ea75.png)
```
public void test() {
  system.out.println("this is a test");
}
```

# 8. 链接
![image](https://user-images.githubusercontent.com/37357447/148870401-bf5b7ce2-33cc-49fe-882d-10fbb62bfafc.png)
你好, 这是一个链接[google](https://www.google.com.hk/)
## 8.2 高级链接(不常用, 可不记) 
![image](https://user-images.githubusercontent.com/37357447/148870563-ab85d41d-3ce1-4583-aa3f-f1a254b749c1.png)

# 9. 图片
## 9.1 常用方案
markdown加载图片  
!&lsqb;替换文本&rsqb;&lpar;链接地址 "可选标题"&rpar;  
![图片不存在](test.com "测试地址")
## 9.2 替换方案(可不记)
![image](https://user-images.githubusercontent.com/37357447/148871232-610b2de6-1fb1-4ac9-9489-6ecf494068cc.png)

# 10. 表格
# 10.1 语法格式
![image](https://user-images.githubusercontent.com/37357447/148871399-9289fc48-aab5-4abe-ae40-fbeb4b6ae1aa.png)
|表头1|表头2|
|-|-|
|单元格|单元格|
|单元格|单元格|
## 10.2 设置对齐
![image](https://user-images.githubusercontent.com/37357447/148872089-bd4c1ca7-40ca-44cb-a1f1-b122e1166d16.png)
|左对齐|居中对齐|右对齐|
|:-|:-:|-:|
|单元格测试单元格|单元格测试单元格|单元格测试单元格|
|单元|单元|单元|

# 11. 高级技巧
## 11.1 锚点 
锚点用于目录, 亦可使用vscode-Markdown All in One一键生成目录  
[markdown的锚点](https://www.jianshu.com/p/6571d37c8060)
## 11.2 vscode-markdown实时预览
[vscode开启markdown实时预览](https://www.cnblogs.com/yourstars/p/15246477.html)
## 11.3 html
不在markdown语法内的html标签, 都可直接在文档内使用,   
例如, ![image](https://user-images.githubusercontent.com/37357447/148873182-b2cd94fb-434e-40be-a402-3e2406e28006.png)
## 11.4 转义
### 11.4.1 使用转义字符
![image](https://user-images.githubusercontent.com/37357447/148873285-4cf28fd4-5428-4607-86ee-3346e2eed0f3.png)  
\*\* 这是一个标题测试
** 列表1
### 11.4.2 使用html转义字符
[w3c-html转义字符](https://dev.w3.org/html5/html-author/charref)
## 11.5 公式
Markdown Preview Enhanced 使用 KaTeX 或者 MathJax 来渲染数学表达式。  
[markdown支持公式-KaTeX](https://github.com/KaTeX/KaTeX)  
[markdown支持公式-MathJax](https://github.com/mathjax/MathJax)
## 11.6 流程图
[如何在Markdown文本中添加流程图，附支持github的方法](https://github.com/DenryDu/DenryDu.github.io/issues/4)
