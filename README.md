# x448-python
Pure Python 3 implementation of x448 formerly used within [noiseprotocol package](https://github.com/plizonczyk/noiseprotocol).

Although it should be compliant with RFC 7748 and is tested (on import) with the vectors provided in RFC, these are all the promises you can get. The implementation may be vulnerable to side channel attacks or worse. You have been warned and are highly encouraged to use [Cryptography](https://github.com/pyca/cryptography/) for your production needs.

## Installation
Install from PyPI: 

`pip install x448-python`
