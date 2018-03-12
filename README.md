params
======

In this repository are prime numbers, some safe primes, that are the result of time consuming calculations, measured in days.  (Some took well over a week.)  Generally speaking, these primes can be used as parameters for the Diffie-Hellman key exchange, and may be reused, repeatedly.  However, being posted on the Internet means you should be suspect.  I strongly urge you to double check them for primality as some nefarious soul may have changed them.

I provide these parameters here because validating their correctness with tools like OpenSSL takes mere seconds.  Use whatever tools you trust, but here is one OpenSSL command you might try.

    $ openssl dhparam -check -in <filepath_to_PEM_block>

THESE NUMBERS ARE MADE AVAILABLE "AS-IS" WITHOUT WARRANTY OR GUARANTEE OF ANY KIND, EXPRESS OR IMPLIED, UNDER ANY AND ALL CONDITIONS, NO EXCEPTIONS.  USE SIGNIFIES ACCEPTANCE OF ALL RISK AND CONSEQUENCES.

These numbers are free for any use.  
