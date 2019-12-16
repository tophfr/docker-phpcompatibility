# Docker image for PHP Compatibility Coding Standard with PHP CodeSniffer

Cf. https://github.com/PHPCompatibility/PHPCompatibility

## How to use it

    docker run --rm -it -v $PWD:$PWD -w $PWD tophfr/phpcompatibility -p .

or

    docker run --rm -it -v $PWD:$PWD -w $PWD tophfr/phpcompatibility -p --runtime-set testVersion 7.3 .
