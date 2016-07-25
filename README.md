Sublime Avalon Completion Package
===============================

目测依赖sublime 自带的完成功能，根据avalon语法字典帮助开发者更便捷高效的使用avalon，在sublime 3上work ok

可以通过设置Avalon语法字典或者直接修改helper.sublime-settings文件来添加更多语法支持

-------
how to use

	1. git clone code to sublime 3/data/packages/AvalonHelper - 
	
	注意：一定是放在插件默认的安装目录下，比如是:
		
		C:\Users\username\AppData\Roaming\Sublime Text 3\Packages\AvalonHelper
		
		Mac则通过“首选项【preferences】 -> 浏览程序包【brow packages】”打开安装目录，直接拷贝过来，ps：avalonHelper的Main.sublime-menu设置可能会修改menu的效果，比如纯英文界面多出一个首选项的汉字item来 = =
		
	1.1 用package controll安装【暂时不要这样做，这样配置就是只读的了。。。】：
	references -> package controll -> add repositoty -> 输入https://github.com/gogoyqj/AvalonHelper
	
	references -> package controll -> install package -> 等待之后，点击弹出的Avalon Helper，完成安装
	
	安装成功之后，需要重新启动一下【读配置失败，见鬼。。。】

	2，ms召唤出属性绑定，组件名字可以召唤出组件自动完成，data召唤出data绑定，data-组件名字召唤出组件属性自动完成(暂时未提供组件属性、接口等字典)

	3，绑定的字典已经迁移到helper.sublime-settings文件内，如有需要自行添加的绑定，请直接修改即可


-------
time line

	2015.8.18 - 添加配置功能、文档入口

	2014.10.17 - 修复多次换行缩进 bug

	2014.10.20 - 添加 w[idget] 召唤出组件列表功能
