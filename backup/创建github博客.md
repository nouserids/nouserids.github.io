# 创建博客
项目地址：https://github.com/Meekdai/Gmeek [链接直达](https://github.com/Meekdai/Gmeek)
1、【创建仓库】点击[通过模板创建仓库](https://github.com/new?template_name=Gmeek-template&template_owner=Meekdai)，建议仓库名称为XXX.github.io，其中XXX为你的github用户名。

2、【启用Pages】在仓库的Settings中Pages->Build and deployment->Source下面选择Github Actions。

3、【开始写作】打开一篇issue，开始写作，并且必须添加一个标签Label（至少添加一个），再保存issue后会自动创建博客内容，片刻后可通过https://xxx.github.io/ 访问（可进入Actions页面查看构建进度）。

4、【手动全局生成】这个步骤只有在修改config.json文件或者出现奇怪问题的时候，需要执行
```
通过Actions->build Gmeek->Run workflow->里面的按钮全局重新生成一次
```
