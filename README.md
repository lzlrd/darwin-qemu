# macOS in QEMU, accelerated by Linux's KVM.

TLDR: Get a BaseSystem.img (QEMU "raw" image file, not a QCOW2 file) and chuck it in `lib/`. Then create a MyDisk.img (again, a QEMU "raw" image) and also chuck that in `lib/`. Then run `./start recovery` and you'll eventually be greated with an installation screen. After the install, just use `./start` for subsequent boots.
