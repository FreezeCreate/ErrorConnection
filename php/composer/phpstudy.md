# PHPStudy环境集成composer的问题

描述：win下安装composer失败，添加openssl扩展后依然失败

解决方案：phpstudy已经安装了从没派送而。只需找到X:\phpStudy\PHPTutorial\tools\composer存在composer目录，打开composer.bat文件，将目录修改为我们将要使用的php和composer目录，Example：

`
D:\phpStudy\PHPTutorial\php\php-7.2.1-nts\php.exe     D:\phpStudy\PHPTutorial\tools\composer\composer.phar %1
`
