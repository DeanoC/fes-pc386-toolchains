# fes-pc386-toolchains

A mirror of the toolchain archives that [DeanoC/fes](https://github.com/DeanoC/fes)'s
pc386 FreeDOS fixture builds with (`sources/misteross/cores/fes-pc386/sim/freedos.lock`,
issue DeanoC/fes#1777). Each file on the release is byte-identical to its upstream copy,
which the lock pins by SHA-256; the builder tries upstream first and this mirror second.

| File | Upstream | Licence |
| --- | --- | --- |
| `ow-snapshot.tar.xz` | [Open Watcom v2 2026-07-13 Build](https://github.com/open-watcom/open-watcom-v2/releases/tag/2026-07-13-Build) | Sybase Open Watcom Public License 1.0 (`license.txt` in the archive); source: [open-watcom/open-watcom-v2](https://github.com/open-watcom/open-watcom-v2) |
| `binutils-ia16-elf_*`, `gcc-ia16-elf_*`, `libnewlib-ia16-elf_*`, `libi86-ia16-elf_*` (`.deb`) | [tkchia/build-ia16 PPA](https://launchpad.net/~tkchia/+archive/ubuntu/build-ia16), noble | GPL-3.0 (gcc, binutils); newlib and libi86 BSD-style. Corresponding source: the PPA's source packages and [tkchia/gcc-ia16](https://github.com/tkchia/gcc-ia16), [tkchia/binutils-ia16](https://github.com/tkchia/binutils-ia16), [tkchia/newlib-ia16](https://github.com/tkchia/newlib-ia16), [tkchia/libi86](https://gitlab.com/tkchia/libi86) |

Nothing here is modified.
