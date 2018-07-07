# Git Pages+Hexo个人博客（适用场景：个人简历、个人简易博客、api说明文档）

# 1.heox生成静态页面模板

# 2.Git创建发布分支（当不是发布到master分支时，分支必须为gh-pages，否则无法将发布的页面设置为仓库的Git Pages，实际上只要有了gh-pages分支，仓库的Git Pages会自动设置 https://kejiqiangqiang.github.io/仓库名/）
# 3.创建一个名称为{username}.github.io的仓局，仓库的Git Pages会自动设成https://kejiqiangqiang.github.io/
# 4.hexo deploy命令：发布hexo（将md文件生成html文件，并打包到public），并自动提交到指定分支，实现一键打包发布
