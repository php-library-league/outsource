# outsource
This repo contains PHP Library outsource folder for demonstrations and PHP unit tests. In order to use it you'll have to clone repository to the root of [PHP Library] and unzip archive.

```bash
# Clone repository
git clone https://github.com/php-library-league/outsource.git

# Unzip zip archive
unzip outsource/archive.zip -d outsource/

# Give full permissions to all outsource folders and files
chmod -R 0777 outsource/

# Run PHPUnit tests
composer run phpunit
```

Please note that in some versions of [PHP Library] you might have to use specific release of outsource folder. Therefore, simply cloning master branch might not be good enough solution. To be secure that it will work, check your version of PHP Library's `README.md` file.

[PHP Library]: https://github.com/90zlaya/php-library
