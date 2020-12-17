# pinpoint-in-symfony

## Steps

> prerequisite 

- [ ] pinpoint-c-agent module installed
- [ ] collect-agent works fine

### 1. Download plugins from pinpoint-c-agent

[ pinpoint-php-plugins.tar.gz ](https://github.com/pinpoint-apm/pinpoint-c-agent/releases/download/V2020.12.17/pinpoint-php-plugins-v0.0.1.tar.gz)

### 2. Make it works

#### 2.1 symfony-demo

1. copy `Plugins` into root
2. composer update
3. cp `Plugins/Framework/symfony/setting.ini` into `Plugins`
4. Update `public/index.php` as `Plugins/Framework/symfony/Readme.md`
