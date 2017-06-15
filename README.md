[Pretty Good Facebook Privacy](https://www.itsc.inf.hs-flensburg.de/development/item/58-pretty-good-facebook-privacy)

PGfbP is a prototype of an Android mobile app to implement a privacy layer on top of facebook. PGfbP can be used to encrypt and decrypt content sent over the facebook network. Example content may be a timeline posting, images, videos or documents. The core of PGfbP is an efficient implementation of a symmetric-key functional encryption scheme. It enables the encryptor to formulate a "policy" which friends are admissible to decrypt the content plaintext. This way, PGfbP overcomes the need to encrypt the content under the key of every recipient and dramatically reduces the communication complexity.


### Goals

PGfbP is an ongoing project and features will be added on demand. The focus is to provide:

 * Privacy of content sent over Facebook
 * Policy-based broadcast encyption of content
 * Privacy of policy to prevent that even legitimate decryptors learn who is entitled to decrypt the content plaintext
 * Prevention at the Web application level against malcious JavaScript attacks, attempting to circuvment the cryptography
 * Maximum efficiency

### Algorithms

PGfbP implements to date:

 * Dual Pairing Vector Space algebra
 * Instantiation of the symmetric-key policy-privat predicate encryption scheme of Shen-Shi-Waters (https://eprint.iacr.org/2008/536) 
 * Cryptographic protocols for key exchange and authenticated encryption


### Citing

If you use PGfbP, please cite using the template below:

    @misc{relic-toolkit,
        author = {Alexandra Dirksen, Sebastian Gajek, Martin Johns and Robert Michael},
        title = {{Pretty Good Facebook Privacy---Securing Users against a Curious Platform}},
        note = {\url{https://www.itsc.inf.hs-flensburg.de/development/item/58-pretty-good-facebook-privacy}},
    }`

### Licensing

PGP is released under an EUPL version 1.2 license to encourage collaboration with other research groups and contributions from the industry. It allows to augment, modify and commercialise the code.

“Copyright: Alexandra Dirksen, Sebastian Gajek and Robert Michael, 06/15/2017; Licensed under the EUPL, with extension of article 5 (compatibility clause) to any licence for distributing derivative works that have been produced by the normal use of the Work as a library.”

### Build instructions

Instructions for building the library can be found in the XXX.


### Disclaimer

PGP is at most alpha-quality software and serves the sole purpose of a proof of concept. Implementations may not be correct or secure. Backward API compatibility with early versions may not necessarily be maintained. Use at your own risk.

**Privacy Warning:** This site tracks visitor information.

