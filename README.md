# pro-short-link-opencart

[![Latest Stable Version](https://img.shields.io/github/v/release/brokeyourbike/pro-short-link-opencart)](https://github.com/brokeyourbike/pro-short-link-opencart/releases)
![GitHub all releases](https://img.shields.io/github/downloads/brokeyourbike/pro-short-link-opencart/total?color=blue)

PRO Short Link

## Use as library

You can call module methods to create short links from the code. Use this snippet as example:

```php
$this->load->model('extension/model/pro_short_link');
$this->model_extension_model_pro_short_link->shortIt('https://super-long-url.com');
```
