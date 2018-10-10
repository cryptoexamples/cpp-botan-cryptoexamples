---
title: C++ Asymmetric String Encryption/Decryption using Botan
keywords: sample
summary: "Asymmetric string encryption/decryption in C++ using Botan"
permalink: c++_cryptography_asymmetric.html
folder: C++ Cryptography
references: [
    # Place a list of references used to create and/or understand this example.
    {
        url: "https://cryptography.io/en/latest/hazmat/primitives/asymmetric/rsa/",
        description: "Cryptography RSA Documentation"
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
tags: [C++, Botan, RSA, Asymmetric, Key, Storage, PKCS#8, X.509, PEM]
---

## Use cases

- Secure message transmission

## Installation

Install Botan:

- [Gettings Started](https://botan.randombit.net/manual/index.html)
- [Building The Library](https://botan.randombit.net/manual/building.html)

## Supported C++ versions

- C++17 (C++1z) (ISO/IEC 14882:2017)

## Example Code for asymmetric string encryption/decryption with C++ using Botan

```c++
{% include_relative src/cryptoexamples/asymmetric.cpp %}
```

{% include links.html %}
