# Changelog
## NodeJs & Angular upgrade Changelog
* 5-17-2024: Setting webpack's uglify plugin "cache" option to false.
    Otherwise a bit of code in said plugin's files was attempting to use the NodeJs crypto module in a deprecated way.