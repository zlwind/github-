# github--research
# Github搜索技巧

## 1 关键字 in

用来限定搜索的范围，可以指定是在名称、描述、readme文档中搜索关键字

- in:name：指定搜索范围是仓库名称
- in:description：指定搜索范围是摘要中
- in:readme：指定搜索范围是readme文档中

~~~
in:name springboot mybatis demo
~~~

## 2 stars forks

通常我们判断一个项目好不好，可以通过项目的stars和fork数量来判断。

方式如下：

- **stars:>** ：筛选stars数量大于某个值的仓库
- **stars:start..end** ：筛选stars数量在start和end区间的仓库
- **fork:>**
- **fork:start..end**

~~~
in:name springboot mybatis demo stars:>50
~~~

## 3 language

这个简单，指定项目的编写语言，如java、python、php等。

~~~
in:description 单点登录 language:java
~~~

## 4 created、pushed

创建日期、更新日期。

~~~
in:description 单点登录 language:java pushed:>2019-12-01
~~~

## 5 size

仓库大小 单位KB

~~~
in:description 单点登录 language:java pushed:>2019-12-01 size:>=500
~~~

## 6 license

开源许可证。

开源许可证即授权条款。开源软件并非完全没有限制。最基本的限制，就是开源软件强迫任何使用和修改该软件的人承认发起人的著作权和所有参与人的贡献。任何人拥有可以自由复制、修改、使用这些源代码的权利，不得设置针对任何人或团体领域的限制；不得限制开源软件的商业使用等。而许可证就是这样一个保证这些限制的法律文件。
常见的开源许可证包括：

- Apache License 2.0

- GNU General Public License v3.0
- MIT License

~~~
// 使用 apache-2.0 协议的仓库
license:apache-2.0 关键词
~~~

## 7 user

仓库持有者

~~~
// 用户google 上传的仓库
user:google 关键词
~~~

## 8 org

组织机构代码

~~~
// 列出org 的 spring-cloud  仓库
org:spring-cloud 
~~~

## 9 高级搜索

> https://github.com/search/advanced

## 10 搜索Github热门

> https://github.com/trending  
>
> https://github.com/topics

**GitHub** **Trend**页面总结了每天/每周/每月周期的热门 Repositories 和 Developers，你可以看到在某个周期处于热门状态的开发项目和开发者。

**GitHub Topic** 展示了最新和最流行的讨论主题，在这里你不仅能够看到开发项目

## 11 关键字awesome

awesome 关键字（优秀的项目、框架、教程等）

## 12 官方搜索说明文档

> https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github

> https://docs.github.com/en/github/getting-started-with-github/keyboard-shortcuts
