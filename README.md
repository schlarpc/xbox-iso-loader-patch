# xbox-iso-loader-patch

Xbox kernel patcher for enabling ISO loading

This was created by rmenhal and xman954, this is just a mirror for my own purposes.

## Building

```
nasm -o patcher.xbe -O0 xboxapp.asm
xbe patcher.xbe -habibi
```

Modern nasm's default optimization breaks the build, so we make sure to disable it.
