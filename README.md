# Homebrew-git-curl-openssl

A formula for `git` with `curl-openssl` and `openssl@1.1`. 

The default `git` formula includes curl which is provided by macOS. This curl includes support for *LibreSSL* and currently does not support TLSv1.3.

This formula allows git to connect to https with TLSv1.3.

## Installation

```shell
brew tap mschoettle/git-curl-openssl
brew install git-curl-openssl
```
