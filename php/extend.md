# PHP扩展

----------

1. 当开启Opcache扩展时请务必注意php.ini验证时间的设置即：`revalidate_freq`,默认设置为60s，即每60s检测是否更新，当我们处在开发环境时，明显存在问题，建议设置为2s
	>来源：[http://www.jackxiang.com/post/8268/](http://www.jackxiang.com/post/8268/)