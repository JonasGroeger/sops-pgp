# sopsinfo

Helps analyzing the GPG contents of a file managed by [SOPS](https://github.com/mozilla/sops/).

## Example

```shell
$ sopsinfo example.json
😀  45CDAE4F06CE8DDFC3EAC3EAC6C033490CF29EF1 -> Jonas Gröger <jonas.groeger@codecentric.de>
😭  Missing identity information for fingerprint 45CDAE4F06CE8DDFC3EAC3EAC6C033490CF2BABE. Do you have the key in the local keyring?
```

# License
MIT
