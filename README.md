sa-saslauthd
============

[![Build Status](https://travis-ci.org/softasap/sa-saslauthd.svg?branch=master)](https://travis-ci.org/softasap/sa-saslauthd)


Example of use: check box-example

Configuration:
```YAML

custom_saslauthd_default_props: []
```

Simple:

```YAML


     - {
         role: "sa-saslauthd",
         custom_saslauthd_default_props: "{{custom_saslauthd_default_props}}"
       }

```


Advanced:

```YAML


     - {
         role: "sa-saslauthd",
         custom_saslauthd_default_props: "{{custom_saslauthd_default_props}}"
       }


```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
