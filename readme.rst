Compile with RISC-V toolchain
-----------------------------------------

Go to the source directory and ``make CC=riscv64-unknown-elf-gcc``.

Notes on run benchmarks with pk
-----------------------------------

There seem to be some problems on creating new files. You need to create the output file first by running the following commands:

- automotive/susan: ``touch output_{small,large}.{smoothing,edges,corners}.pgm``
- automotive/lame: ``touch output_{small,large}.mp3``
- blowfish: ``touch output_{small,large}.{enc,asc}``
- rijndael: ``touch output_{small,large}.{enc,dec}``
