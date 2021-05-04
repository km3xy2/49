05.07 14:48
packagist 软件包仓库，扩展仓库，扩展类库，下载，上传，termux安装composer然用composer命令下载扩展
类
库


扩展


https://packagist.org/

英文官方//软件包仓库

http://packagist.p2hp.com/

中文网页//软件包仓库

termux安装composer

输入
$  pkg  install composer

安装完之后就能用
composer下载扩展包了

在官方https://packagist.org/

搜索想要的扩展，复制下载命令下载即可
如果想要找log扩展类包

在官方https://packagist.org/

搜索框里搜索log，复制以下命令来安装log扩展包


$   composer require monolog/monolog


下载到termux内部导入引用即可

新建php文件里导入类库引用即可


$ composer require monolog/monolog

Using version ^2.2 for monolog/monolog
./composer.json has been updated
Running composer update monolog/monolog
Loading composer repositories with package information
Updating dependencies
Lock file operations: 2 installs, 0 updates, 0 removals
  - Locking monolog/monolog (2.2.0)
  - Locking psr/log (1.1.4)
Writing lock file
Installing dependencies from lock file (including require-dev)
Package operations: 2 installs, 0 updates, 0 removals
  - Downloading psr/log (1.1.4)
  - Downloading monolog/monolog (2.2.0)
  - Installing psr/log (1.1.4): Extracting archive
  - Installing monolog/monolog (2.2.0): Extracting archive
11 package suggestions were added by new dependencies, use `composer suggest` to see details.
Generating autoload files
1 package you are using is looking for funding.
Use the `composer fund` command to find out more!
~ $ ls
composer-setup.php  composer.phar  vendor
composer.json       downloads      www
composer.lock       storage
~ $ ls storage
dcim       movies  pictures
downloads  music   shared

~ $ cd
~ $ ls -a
.              .viminfo            downloads
..             composer-setup.php  storage
.bash_history  composer.json       vendor
.composer      composer.lock       www
.termux        composer.phar

~ $ ls vendor
autoload.php  composer   monolog    psr


~ $ ls vendor/monolog/monolog/

CHANGELOG.md  UPGRADE.md         src
LICENSE       composer.json
README.md     phpstan.neon.dist

~ $ ls vendor/monolog/monolog/src
Monolog

~ $ ls vendor/monolog/monolog/src/Monolog
DateTimeImmutable.php  Registry.php
ErrorHandler.php       ResettableInterface.php
Formatter              SignalHandler.php
Handler                Test
Logger.php             Utils.php
Processor
~ $

扩展包默认下载到termux内部vendor文件夹内





