# -m = RAM e.g. 256M = 256 megabytes of RAM
# -cpu = Specifies CPU, e.g. qemu64 CPU
#  -drive = Configuration of the hard drive
#  -net = Network e.g. -net none (because we're not using network yet)
run:
	qemu-system-x86_64 -m 256M -cpu qemu64 -drive if=pflash,format=raw,unit=0,file="OVMFbin/OVMF_CODE-pure-efi.fd",readonly=on -drive if=pflash,format=raw,unit=1,file="OVMFbin/OVMF_VARS-pure-efi.fd" -net none

