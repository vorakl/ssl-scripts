# ssl-scripts

Collection of scripts  for SSL management, based on the openssl command line tool

## Install

1. Copy scripts from ./scripts/ to somewhere in your $PATH
2. Update directories in /etc/openssl.conf as in example of openssl.conf

## Usage

    cd /etc/ssl && <script> <parameters>

## Contents

- `sslinfocrl`   Get info about revocation list
- `sslinfocrt`   Get info about certificate
- `sslinfokey`   Get info about key
- `sslinforeq`   Get info about request

- `sslmakeca`    Create CA
- `sslmakecrl`   Create a revocation list
- `sslmakecrt`   Create a certificate
- `sslmakedh`    Create a diffie-hellman key
- `sslmakereq`   Create a request

- `sslrvkcrt`    Revoke a certificate
