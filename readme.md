# think-whoops

让Whoops接管ThinkPHP6异常, Whoops提供stackbased错误捕获及超美观的错误

[![Latest Stable Version](https://poser.pugx.org/yzh52521/think-whoops/version)](https://packagist.org/packages/yzh52521/think-whoops)
[![Total Downloads](https://poser.pugx.org/yzh52521/think-whoops/downloads)](https://packagist.org/packages/yzh52521/think-whoops)
[![License](https://poser.pugx.org/yzh52521/think-whoops/license)](https://packagist.org/packages/yzh52521/think-whoops)


## 安装
```php
$ composer require yzh52521/think-whoops
```

## 开启/关闭接管
开启 `APP_DEBUG` 才正常接管， 关闭默认转交ThinkPHP处理
`config/whoops.php`
```php
 <?php
 
 return [
  'enable' = true
 ];
```

## 打开编辑器
帮助您从异常堆栈跟踪中打开代码编辑器  

支持编辑器 `sublime,textmate,emacs,macvim,phpstorm,idea,vscode,atom,espresso  `

`config/whoops.php`
```php
 <?php
 
 return [
   'editor' = 'vscode'
 ];
```

