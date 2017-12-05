# lemp7-nodejs:ffmpeg

lemp with php7 and any critical extensions and nodejs and npm with nvm

lemp7-nodejs image is base on [lemp-php7-full image](https://github.com/Mehrdad-Dadkhah/lemp-php7-full)

# lemp-php7-full
nginx with php7 full pack and supervisord

It is base on [php7 image](https://hub.docker.com/r/mehrdadkhah/php7) that contains:

 - last stable version of Redis extension (official version)
 - Intl extension (official version)
 - Apcu extension ([official build for php7](https://pecl.php.net/package/APCu))
 - Soap
 - PDO (MySQL, PostgreSQL, Sqlite)
 - GD
 - iconv
 - mbstring
 - composer
 - xdebug

+ in ffmpeg tag add [FFMpeg](https://github.com/FFmpeg/FFmpeg) installation for video related projects.

and in ffmpeg tag image contain latest version of FFmpeg.
----------
##usage

    docker pull mehrdadkhah/lemp7-nodejs:ffmpeg