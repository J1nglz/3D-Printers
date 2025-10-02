# 3D Printers - Software Configurations & References

This repository contains versions of 3D printer software configurations and references to various git repositories that hold printer profiles used by printers today.

## Repository Structure

```
3D-Printers/
├── configurations/          # Printer software configuration files
│   ├── marlin/             # Marlin firmware configurations
│   ├── klipper/            # Klipper configurations
│   ├── prusa/              # PrusaSlicer profiles
│   ├── cura/               # Cura slicer profiles
│   └── orcaslicer/         # OrcaSlicer profiles
├── references/             # References to external git repositories
│   └── profile-repos.md    # List of external profile repositories
└── README.md               # This file
```

## Configurations Directory

The `configurations/` directory contains saved versions of 3D printer software configurations organized by software type:

- **marlin/**: Marlin firmware configuration files (Configuration.h, Configuration_adv.h)
- **klipper/**: Klipper printer.cfg files and related configurations
- **prusa/**: PrusaSlicer configuration bundles and profiles
- **cura/**: Cura slicer profiles and settings
- **orcaslicer/**: OrcaSlicer profiles and configurations

Each subdirectory should be organized by printer model or configuration name for easy reference.

## References Directory

The `references/` directory contains markdown files with links to external git repositories that maintain 3D printer profiles and configurations.

## Contributing

When adding configurations:
1. Create a subdirectory for your printer model or configuration name
2. Include a README.md in the subdirectory with:
   - Printer model/name
   - Software version
   - Date of configuration
   - Any special notes or modifications
3. Add your configuration files

When adding references:
1. Add the repository URL to the appropriate section in `references/profile-repos.md`
2. Include a brief description of what the repository contains
3. Note the primary printer models or brands supported

## Version Control

All configuration versions are tracked through git commits. To see the history of a specific configuration:
```bash
git log --follow -- path/to/configuration/file
```

## License

Please respect the licenses of any configurations or profiles you add to this repository.