# auto-buildroot

*Build debug rootfs with one cmdline.*

## Usage

```
$ ./start_build.sh
usage: start_build.sh <build_target>

build_targets: (le: little_endian, be: big_endian)
* riscv64
* ppc64
* mips64
* mips64r6
* mips32r2el
* mips64r6el
* riscv32
* mips32r6
* mips64el
* mips32r2
* ppc
* s390x
* ppc64_le
* aarch64_le
* mips32r6el
* armhf_le
```

For example, I want to build armhf_le rootfs:
```
$ ./start_build.sh armhf_le
< some output ...>
< ... >
< ... >
[+] Build result is at xxx/armhf_le.tar.gz

$ ls
armhf_le.tar.gz
```