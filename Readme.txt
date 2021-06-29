Description

AVR128DA32 / Atmega128 microcontroller based open source EID smartcard with
RSA (512-2048) and ECC - ECDSA and ECDH operations on prime192v1,
prime256v1, secp384r1, secp256k1 and secp521r1.  Compatible with MyEID card
from Aventra.  Supported in windows and linux by opensc package.  Allow
about 64KiB space for keys/certificates.  PKCS#15 structure supported.

USB token with CCID interface based on atmel xmega128a4u with same features
as card.

Online HTML doc https://popovec.github.io/OsEID/

PDF documentation:  https://oseid.sourceforge.io (download last OsEID tarball)

Precompiled card and token hex files can be found in download directory.

files in download directory are compiled by:

avr-libc                     1:2.0.0+Atmel3.6.1-2
binutils-avr                 2.26.20160125+Atmel3.6.1-4
gcc-avr                      1:5.4.0+Atmel3.6.1-2
