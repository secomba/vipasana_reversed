# Vipasana reversed encryption code

This is the encryption routine of the Vipasana ransomware, MD5: 2aea3b217e6a3d08ef684594192cafc8. Extracted during the analysis of the virus over at [boxcryptor](https://www.boxcryptor.com/en/blog/post/a-close-look-at-ransomware-vipasana-part-i/).

For a description of its inner workings and a list of vulnerabilities, check out our [blog article](https://www.boxcryptor.com/en/blog/post/a-close-look-at-ransomware-vipasana-part-i/)

### Decrypted components

* Vipasana PRNG algorithm
* Vipasana stream cipher algorithm
* additionally encryption example

The code assumes that the initial state of the PRNG is known.