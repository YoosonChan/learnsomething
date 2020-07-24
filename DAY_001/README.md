# DAY 001 每个程序员必不可少的Hello world.

每个程序员学习一门新的编程语言都是从hello world开始。

下面我就为大家分享一下如果编写并显示出hello world的网页吧。

## 准备工作

### 需要的工具
> tips: 下载工具一定要在官网下载
1. 编辑器：编写代码需要使用的工具。
    >名称：Visual Studio Code（简称VSCode）     
    >下载地址：https://code.visualstudio.com/Download
2. 浏览器：显示并运行自己编写代码所实现的网页的工具。
    >名称：谷歌浏览器（Chrome）     
    >下载地址：https://www.google.cn/chrome/
    
    > tips: 其他浏览器也可以，以上浏览器只为推荐，可根据自己爱好选择。

### 创建编程目录
> tips：根据自己个人爱好创建即可

1. 创建目录。选择自己喜欢的目录即可。
2. 在目录中打开编辑器。进入到自己创建的目录之后，点击鼠标右键，出现右键菜单。菜单中有一个『通过Code打开』选项。点击选项，系统就会在该目录下打开vscode编辑器。
    > 右键菜单效果：
    ![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/menu.png)

    > tips: 右键菜单中含有『通过Code打开』选项的前提是，已经安装了vscode编辑器。

#### 最终效果
![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/directory.png)

#### 界面说明
打开编辑器之后，效果如上图所示，如果是第一次安装会有一个welcome的文件会被打开，可能会看不到文件目录，此时就需要点击左上角文件列表选项按钮（按钮名字随便起的，认准那个图标就行）。点击之后就会出现效果图中的样子。
> tips: 如果你不能忍受界面是英文，就可以选择左侧五个按钮中的最下面一个插件按钮，在搜索框中搜索“chinese”关键字，通常是第一个，然后点击install按钮安装插件，然后重启编辑器就可以了。

### 创建页面编写代码
鼠标移至左侧目录，在你喜欢的目录的名称旁边会出现四个操作按钮，如图：
![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/create.png)
> 第一个按钮表示创建文件，第二个按钮表示创建目录。

1. 点击第一个按钮创建文件。
点击之后会让你输入文件名称，可以输入```index.html```,然后回车完成创建。
    > 文件名称可以根据自己喜好命名，但是后缀```.html```不能变，以为后缀名是表示文件是什么类型文件的标志，失去标志就会石乐志

2. 代码界面。
在文件创建之后，界面右侧就会显示刚才创建文件的内容（当然最开始肯定是光光的啦）。

3. 编写代码。点击代码区，输入```html```四个字符，通常情况下，代码的下方会出现提示，如图：
![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/html.png)
选择```html:5```选项然后回车，编辑器就会自动补全代码。
效果如图所示：
![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/init.png)

4. 没有提示的情况。
如果没有提示就自己敲出来吧，当然你可以选择复制（Ctrl + C），粘贴（Ctrl + V）到编辑器里。
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

5. 写出hello world

    html文件是一个由无数个方括号组成的**标签**形成的文件，每个标签都有自己的意义和功能。

    当然，我们这里要在页面显示hello world就需要把代码写在标签```<body></body>```之中。其中每个网页在浏览器输入地址的地址栏上方有一个网页的标题，编写代码的时候就可以把标题内容写在```<title></title>```标签中。标签中的斜杠（/）表示的就是结束这个标签的标志。

    效果如图：
    ![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/hello_world.png)

6. 保存代码（Ctrl + S）

7. 运行代码
    保存代码之后，我们的第一个hello world网页就编写完成了。
    我们来到我们创建的目录中双击html文件就可以看到效果啦。
    > tips: 如果你忘记了你的目录在哪里还有一招,点击一下左侧目录空白处，按快捷键 **Shift + Alt + R**就可以直接打开你创建的目录的位置。

    > tips: 如果你双击html文件不能打开网页，或者不是你想要的浏览器打开的话，你可以选择文件右键点击选择 **打开方式** 或者 **选择默认打开程序**。
8. 最终效果
    ![avatar](https://github.com/YoosonChan/learnsomething/blob/master/DAY_001/md_img/fin.png)