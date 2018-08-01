# http-client
[![Latest Stable Version](https://poser.pugx.org/fts/http-client/v/stable)](https://packagist.org/packages/fts/http-client)
[![Total Downloads](https://poser.pugx.org/fts/http-client/downloads)](https://packagist.org/packages/fts/http-client)
[![License](https://poser.pugx.org/fts/http-client/license)](https://packagist.org/packages/fts/http-client)

# 功能
* 发送http请求
# 安装
    composer require fts/http-client
### 添加服务提供者
打开 `config/app.php` 并添加以下内容到 providers 数组:
    
    fts\HttpClient\HttpClientServiceProvider.php::class
# 用法
    http_request($type, $url, $options = array())
