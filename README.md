PKCS #11 key wrapping and unwraping tests..
=======

# Introduction

Recently I had to prototype some PKCS#11 code to test if the API supported
symmetric key wrapping and double wrapping using RSA and ECDSA public keys.
Coding with C, reading huge pdf docs and header files is just annoying. This
is why I decided to start a PKCS#11 Object Oriented and well documented library.
I hope it helps me and my team mates with our current projects. Moreover, if
it suits you, please feel free to use, share and contribute :)

My goal is to implement this library to work with simple use cases and less code.
If you wish to implement more complex applications, I recommend taking a look at
Libp11 from OpenSC project.

Under development as of Oct 2015 
Lucas Perin
