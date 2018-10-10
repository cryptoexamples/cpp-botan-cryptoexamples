---
title: C++ String Signature using Botan
keywords: sample
summary: "String signature in C++ using Botan"
permalink: c++_cryptography_signature.html
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
tags: [C++, Botan, Asymmetric, Key, ECDSA, secp512r1, EMSA1(SHA-256)"]
---

## Use cases

- Message sender authentication

## Installation

Install Botan:

- [Gettings Started](https://botan.randombit.net/manual/index.html)
- [Building The Library](https://botan.randombit.net/manual/building.html)

## Supported C++ versions

- C++17 (C++1z) (ISO/IEC 14882:2017)

## Example Code for string signature in C++ using Botan

```c++
{% include_relative src/cryptoexamples/hashing.cpp %}
```

{% include links.html %}
