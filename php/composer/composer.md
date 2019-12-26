# Composer


----------

1. composer自动加载方式之：classmap
	
	在composer.json写入加载规则，如：`"autoload": {
        "classmap" : [
            "app/controllers",
            "app/model"
        ]
    }` 表示这两个目录的命名空间，使用`composer dump-autoload`在`vendor/composer/autoload_classmap.php`生成对应的路径数组存储起来，以便被自动载入。Tips:在每次有新文件时都要`dump-autoload`生成对应路径，特别是在自建包或者原生引用其他包时需特别注意。

