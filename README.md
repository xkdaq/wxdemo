##demo用来记笔记

###1.android studio 中的更改commit用户

打开Git所在文件中的git.cmd.exe输入以下命令可更改用户名和邮箱：
- git config --global user.name "xk"
- git config --global user.email 1490552590@qq.com

###2.android studio 3.0遇到问题:

- studio3.0和butterknife高版本(8.8.1)编译冲突出现问题  
     Error:Unable to find method 'com.android.build.gradle.api.BaseVariant.getOutputs()Ljava/util/List;  
     降低版本或者add maven(参考项目androidone)

###3.android项目中的的配置  
- android 中使用Lambda表达式  
     http://blog.csdn.net/sbsujjbcy/article/details/46956611  
     我发现在新的版本中可以不用加上apply plugin: 'me.tatarka.retrolambda'这个了.


##文章
1.[Android应用发布](https://github.com/xkdaq/wxdemo/blob/master/article/Android%E5%BA%94%E7%94%A8%E5%8F%91%E5%B8%83.md)