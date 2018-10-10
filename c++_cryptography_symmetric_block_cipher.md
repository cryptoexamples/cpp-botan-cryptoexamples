---
title: C++ Symmetric String Encryption/Decryption with a Block Cipher using Botan
keywords: sample
summary: "Symmetric string encryption/decryption with a block cipher in C++ using Botan"
permalink: c++_cryptography_symmetric_block_cipher.html
folder: C++ Cryptography
references: [
    # Place a list of references used to create and/or understand this example.
    {
        url: "https://cryptography.io/en/latest/hazmat/primitives/symmetric-encryption/?highlight=AES",
        description: "Cryptography Symmetric Encryption/Decryption Documentation"
    }
]
authors: [
    {
        name: "Jakob Benz"
    }
]
# List all reviewers that reviewed this version of the example. When the example is updated all old reviews
# must be removed from the list below and the code has to be reviewed again. The complete review process
# is documented in the main repository of CryptoExamples
current_reviews: [

]
# Indicates when this example was last updated/created. Reviews don't change this.
last_updated: "2018-10-01"
tags: [C++, Botan, AES, Symmetric, Key, Block Cipher, AES-256]
---

## Use cases

- Random key generation
- Key-based block cipher string encryption/decryption

## Installation

Install Botan:

- [Gettings Started](https://botan.randombit.net/manual/index.html)
- [Building The Library](https://botan.randombit.net/manual/building.html)

## Supported C++ versions

- C++17 (C++1z) (ISO/IEC 14882:2017)

## Example Code for symmetric block cipher string encryption/decryption with C++ using Botan

```c++
{% include_relative src/cryptoexamples/symmetric_block_cipher.cpp %}
```

{% include links.html %}
