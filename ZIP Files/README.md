* `zip2john`

    Brute force password protected zip files.

``` bash
$ zip2john protected.zip > protected.john
$ john --wordlist=/usr/share/wordlists/rockyou.txt protected.john
```

* [`bkcrack`](https://github.com/kimci86/bkcrack)

    Crack ZipCrypto Store files. Need some plaintext to work.

