# PHP Pre-commit Linter, Analyzer and Tester

## About
Pre-commit hook to check code-standards, find bugs, validate architecture layers and run unit-tests with:

 - [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)

 - [PHPStan](https://github.com/phpstan/phpstan)

 - [Deptrac](https://github.com/qossmic/deptrac)

 - [Codeception](https://github.com/Codeception/Codeception)

## Installation

Just copy **pre-commit** file to **.git/hooks**

## Settings

In **pre-commit** file you can set:

**DEBUG** - Enable debug mode. Output full messages from analyzers and unit-tests runner

**DOCKER_CONTAINER_NAME** - Name of your PHP Docker container

**DOCKER_CONTAINER_USER** - User of your PHP Docker container 

**TMP_STAGING** - Path to temporary directory for staged files copies

**PHP_CS_CHECK** - Enable PHP_CodeSniffer check

**PHP_STAN_CHECK** - Enable PHPStan check

**PHP_DEPTRAC** - Enable Deptrack check

**PHP_UNIT_CHECK** - Enable unit-tests run

**PHP_CS_CONFIG_PATH** - path to PHP_CodeSniffer config (*phpcs.xml* by default)

**PHP_STAN_MEMORY_LIMIT** - memory limit to run PHPStan (*4G* by default)

**PHP_STAN_BIN_PATH** - path to PHPStan (*vendor/bin/phpstan* by default)

**DEPTRAC_CONFIG_FILE** - path to Deptrac config (*deptrac.phar* by default)

**UNIT_TESTS_BIN_PATH** - path to Codeception (*vendor/bin/codecept* by default)

   
