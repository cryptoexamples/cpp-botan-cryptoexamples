---
title: C++ String Hashing using Botan
keywords: sample
summary: "String hashing in C++ using Botan"
permalink: c++_cryptography_hashing.html
folder: C++ Cryptography
references: [
    # Place a list of references used to create and/or understand this example.
    {
        url: "https://cryptography.io/en/latest/hazmat/primitives/cryptographic-hashes/",
        description: "Cryptography Message digests Documentation"
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
tags: [C++, Botan, Hashing, SHA, SHA-512]
---

## Use cases

- Verifying whether a string has been changed or not.

## Installation

Install Botan:

- [Gettings Started](https://botan.randombit.net/manual/index.html)
- [Building The Library](https://botan.randombit.net/manual/building.html)

## Supported C++ versions

- C++17 (C++1z) (ISO/IEC 14882:2017)

## Example Code for string hasing with C++ using Botan

```c++
{% include_relative src/cryptoexamples/hashing.cpp %}
```

{% include links.html %}
