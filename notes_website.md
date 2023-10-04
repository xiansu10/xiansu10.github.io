1. Bibliography中不可以没有year={}
2. gh-pages是用来存放一些public的文件, 比如blog文件, 简历等
3. master分支用来存放源代码
4. The default is purple, but you can quickly change it by editing the `--global-theme-color` variable in the `_sass/_themes.scss` file. Other color variables are listed there as well. The stock theme color options available can be found at `_sass/_variables.scss`. 
5. LiveReload address: http://0.0.0.0:35729
6. Auto-regeneration: enabled for '/srv/jekyll'
7. Server address: http://0.0.0.0:8080
8. image magic 可能会产生很多的错误, 如果遇到和图片相关的错误把这个设置成false
9. 为了移除Blog子菜单
    1. 在_includes/header.html中注释掉了与blog相关的lines
    2. 在\_config.yml中注释掉了与blog相关的lines
10. for removing 'repositories' in header
    1. Open _pages/repositories.md
    2. change `nav: true` to `nav:false`

11.about_einstein.md是用来显示在people中的, about.md中的才是显示在主页的

12.显示底部的social icon的选项是在about.md里