# git-hook-drupal-lint

### Install on your GIT project
```shell
curl -o .git/hooks/pre-commit https://raw.githubusercontent.com/aramean/git-hook-drupal-lint/main/pre-commit && chmod 777 .git/hooks/pre-commit
```

### Uninstall from your GIT project
```shell
rm -fr .git/hooks/pre-commit
```

### Test on your GIT project
```shell
git commit
```
---

### Configuration
* 0 to Disable
* 1 to Enable
* "path to binary" to override drupal vendor path

#### .git/hooks/pre-commit
```shell
# PHP
PHP_BIN=1

# Code Sniffer
PHPCS_BIN=1

# PHP Stan
PHPSTAN_BIN=1

```
