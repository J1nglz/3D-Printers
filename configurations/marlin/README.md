# Marlin Firmware Configurations

This directory contains Marlin firmware configuration files for various 3D printers.

## Structure

Organize configurations by printer model:
```
marlin/
├── ender3/
│   ├── Configuration.h
│   ├── Configuration_adv.h
│   └── README.md
├── cr10/
└── prusa-mk3/
```

## Adding a Configuration

1. Create a folder with your printer model name
2. Add your `Configuration.h` and `Configuration_adv.h` files
3. Include a README.md with:
   - Marlin version used
   - Printer specifications
   - Any custom modifications
   - Build date
   - Hardware version

## Resources

- [Marlin Firmware](https://marlinfw.org/)
- [Marlin GitHub](https://github.com/MarlinFirmware/Marlin)
- [Marlin Configuration Examples](https://github.com/MarlinFirmware/Configurations)
