Config files for an golden Debian 12 netinstall qcow2 image created in Packer.

How to use:

1. Modify files as needed

2. Spell the magic
```
packer build debian12-kvm.json
```

3. Check `output-qemu` for the final image
