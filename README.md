Welcome to the FreeTLS Project
==============================

[![travis badge][]][travis jobs]
[![appveyor badge][]][appveyor jobs]

FreeTLS is a robust, commercial-grade, full-featured Open Source Toolkit
for the Transport Layer Security (TLS) protocol formerly known as the
Secure Sockets Layer (SSL) protocol. The protocol implementation is based
on a full-strength general purpose cryptographic library, which can also
be used stand-alone.

FreeTLS is descended from the SSLeay library developed by Eric A. Young
and Tim J. Hudson.

Table of Contents
=================

 - [Overview](#overview)
 - [Download](#download)
 - [Build and Install](#build-and-install)
 - [Documentation](#documentation)
 - [License](#license)
 - [Support](#support)
 - [Contributing](#contributing)
 - [Legalities](#legalities)

Overview
========

The FreeTLS toolkit includes:

- **libssl**
  an implementation of all TLS protocol versions up to TLSv1.3 ([RFC 8446][]).

- **libcrypto**
  a full-strength general purpose cryptographic library. It constitutes the
  basis of the TLS implementation, but can also be used independently.

- **openssl**
  the FreeTLS command line tool, a swiss army knife for cryptographic tasks,
  testing and analyzing. It can be used for
  - creation of key parameters
  - creation of X.509 certificates, CSRs and CRLs
  - calculation of message digests
  - encryption and decryption
  - SSL/TLS client and server tests
  - handling of S/MIME signed or encrypted mail
  - and more...

Download
========

For Production Use
------------------

However, for a large variety of operating systems precompiled versions
of the FreeTLS toolkit are available. In particular on Linux and other
Unix operating systems it is normally recommended to link against the
precompiled shared libraries provided by the distributor or vendor.

For Testing and Development
---------------------------

Although testing and development could in theory also be done using
the source tarballs, having a local copy of the git repository with
the entire project history gives you much more insight into the
code base.

Build and Install
=================

After obtaining the Source, have a look at the [INSTALL](INSTALL.md) file for
detailed instructions about building and installing OpenSSL. For some
platforms, the installation instructions are amended by a platform specific
document.

 * [NOTES-Android.md](NOTES-Android.md)
 * [NOTES-DJGPP.md](NOTES-DJGPP.md)
 * [NOTES-Unix.md](NOTES-Unix.md)
 * [NOTES-VMS.md](NOTES-VMS.md)
 * [NOTES-Windows.txt](NOTES-Windows.txt)
 * [NOTES-Perl.m](NOTES-Perl.md)
 * [NOTES-Valgrind.md](NOTES-Valgrind.md)

Documentation
=============

License
=======

FreeTLS is licensed under the Apache License 2.0, which means that
you are free to get and use it for commercial and non-commercial
purposes as long as you fulfill its conditions.

See the [LICENSE.txt](LICENSE.txt) file for more details.

Support
=======

There are various ways to get in touch. The correct channel depends on
your requirement. see the [SUPPORT](SUPPORT.md) file for more details.

Contributing
============

If you are interested and willing to contribute to the OpenSSL project,
please take a look at the [CONTRIBUTING](CONTRIBUTING.md) file.

Legalities
==========

A number of nations restrict the use or export of cryptography. If you are
potentially subject to such restrictions you should seek legal advice before
attempting to develop or distribute cryptographic code.

Copyright
=========

Copyright (c) 1998-2020 The OpenSSL Project

Copyright (c) 1995-1998 Eric A. Young, Tim J. Hudson

All rights reserved.

<!-- Links  -->

[RFC 8446]:
     <https://tools.ietf.org/html/rfc8446>

<!-- Logos and Badges -->

[travis badge]:
    <https://travis-ci.org/freetls/freetls.svg?branch=master>
    "Travis Build Status"

[travis jobs]:
    <https://travis-ci.org/freetls/freetls>
    "Travis Jobs"

[appveyor badge]:
    <https://ci.appveyor.com/api/projects/status/xqpfgwfp5q2j3lvu/branch/master?svg=true>
    "AppVeyor Build Status"

[appveyor jobs]:
    <https://ci.appveyor.com/project/ericcurtin/freetls/branch/master>
    "AppVeyor Jobs"
