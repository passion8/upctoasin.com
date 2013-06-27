UPCtoASIN.com
=============

UPCtoASIN.com -- A website to easily convert a UPC to an ASIN.

Installation
------------

    git clone git@github.com:AlexCline/upctoasin.com.git
    cd upctoasin.com
    npm install
    make test
    node app.js

Also needed is a file at `conf/aws.conf` with the following contents:

    AWSAccessKeyId: YOURAWSACCESSID
    AWSSecretKey: YOURAWSSECRETKEY
    AWSTagId: YOURAWSASSOCTAGID

### Mac OS X

You'll also need to specify the path to XCode before you run `npm install`.  This is needed for the `sqlite3` module.

    sudo xcode-select --switch /usr/bin

### CentOS

You'll need the following packages to build the required modules:

    sudo yum install make