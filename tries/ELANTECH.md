# vendor: 0x4f3 Product: 0x3140 MSFT0001

If we force the kernel to use ietp(4),
we can caught an interruption with the right click, only once.

```
Note: Neither ims(4)/imt(4) with hidms_intr, has been triggered an
interruption.
```

How drivers are attached on OpenBSD.
ietp -> dwiic -> glkgpio -> acpi

```
Note:
MSFT0001 is not configured by ACPI (should check Microsoft Documentations)
```
