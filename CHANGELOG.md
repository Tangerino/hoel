# Hoel Changelog

## 1.4.6

- CMake scripts improvements

## 1.4.5

- Add config file hoel-cfg.h dynamically built with the options
- Improve CI

## 1.4.4

- Add Travis CI
- Change cmake option BUILD_TESTING to BUILD_HOEL_TESTING
- Add RPM in CMake script package

## 1.4.3

- Fix memory leak
- Fix pkg-config information, add requires fields as mentionned in babelouest/ulfius#62
- Improve example_mariadb_json.c to make it more readable and understandable, clean code
- Removing the my_global.h include in hoel-mariadb.c
- Fix static library output file name babelouest/ulfius#55

## 1.4.2

- Fix Makefile soname

## 1.4.1

- Add Debian hardening patch on Makefile

## 1.4

- Add CMake installation script
- Various bugfixes
