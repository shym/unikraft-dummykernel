# Dummy unikraft unikernel

Dummy unikernel just to compile the dependencies for the OCaml runtime and
extract from the intermediate `.cmd` files the list of necessary arguments to
build a dedicated toolchain (in particular a `ARCH-unikraft-ocaml-gcc` compiler)
to compile and / or link OCaml programs.

## Logs

`logs/` contains a capture of the key commandlines to compile and link the
unikernel on `x86_64`.
