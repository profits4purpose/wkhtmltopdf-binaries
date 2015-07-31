# wkhtmltopdf for OSX 0.12.1 qtwebkit

[All the binaries for OSX and Ubuntu 14.04 Trusty from http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profits4purpose/wkhtmltopdf-binaries": "0.12.1"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```
vendor/bin/wkhtmltopdf-amd64-osx

vendor/bin/wkhtmltopdf-linux-trusy-amd64
```

Enjoy the bin files!
