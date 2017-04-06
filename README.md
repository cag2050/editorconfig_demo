# editorconfig_demo
EditorConfig使用（代码规范）

在webStorm中默认是支持editorConfig插件的，那么我们需要在webStorm中自定义editorConfig的配置怎么来做？  
第一步：打开webStrome > File > settings（快捷键ctrl+alt+s）；  
第二步：找到Editor > Code Style 并点击它，在下面会有一个Enable EditorConfig support（启动EditorConfig的支持），点它前面的复选框选中它；  
第三步：在复选框的后面有一Export按钮，它是导出editorConfig配置文件；我们点一下它，然后点确定；这时在你的项目中已经有了一个.editorConfig配置文件了；  
[*]  
charset=utf-8  
end_of_line=crlf  
insert_final_newline=false  
indent_style=space  
indent_size=2  
到此我们已经把webStorm中的editorConfig配置好了，现在缩进是4个空格，把它改成2个空格 ，然后打开一个js文件按shift+ctrl+f格式化时，js文件里的代码就会按2个空格来缩进，这时说明插件启动成功！
