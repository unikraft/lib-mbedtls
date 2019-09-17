libmbedtls for Unikraft
===================
This is a port of mbed TLS to Unikraft. The port has a number of
dependencies. To meet them, ensure that you have the following libs
added to your LIBS variable in your app's Makefile:

* CXX standard library, e.g. `libunwind`, `compiler-rt`, `libcxxabi`,
`libcxx`
* `lwip`
* `libc`, e.g. `newlib`

Also make sure that mbed TLS comes after compiler-rt .

Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository for further information.


