# Klipper Configurations

This directory contains Klipper configuration files for various 3D printers.

## Structure

Organize configurations by printer model:
```
klipper/
├── voron-2.4/
│   ├── printer.cfg
│   ├── macros.cfg
│   └── README.md
├── ender3/
└── custom-corexy/
```

## Adding a Configuration

1. Create a folder with your printer model name
2. Add your `printer.cfg` and any additional config files
3. Include a README.md with:
   - Klipper version
   - Printer specifications
   - MCU details
   - Date of configuration
   - Any custom macros or modifications

## Resources

- [Klipper Documentation](https://www.klipper3d.org/)
- [Klipper GitHub](https://github.com/Klipper3d/klipper)
- [Klipper Config Reference](https://www.klipper3d.org/Config_Reference.html)
