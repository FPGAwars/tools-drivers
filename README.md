# Tools-drivers

**IMPORTANT** [Dec 25th 2025] The main branch of this repository was changed from `master`
to a new branch called `main` and the old `master` branch is now frozen in read-only state. Please submit all future pull requests on the new branch `main`. The frozen branch should keep serving
this URL https://raw.githubusercontent.com/fpgawars/tools-drivers/master/VERSION to Apio versions
before 1.2.0.

> **Note:** Please **do not** open issues in this repository.
> For any questions, discussions, or bug reports, use the [main Apio repository](https://github.com/FPGAwars/apio).

<br>

This is an [Apio](https://github.com/FPGAwars/apio) package that contains the drivers and tool for Windows.

```
package/
├── bin
│   ├── ftdi_eeprom.exe
│   ├── lsftdi.exe
│   ├── lsusb.exe
│   ├── serial_install.exe
│   └── zadig.exe
├── package.json
└── share
    └── zadig.ini
```

The director 'package' is compressed as the 'drivers' package file.
