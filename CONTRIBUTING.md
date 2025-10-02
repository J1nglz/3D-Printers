# Contributing Guide

Thank you for contributing to the 3D Printers configuration repository! This guide will help you add your configurations or references properly.

## How to Contribute

### Adding Printer Configurations

1. **Fork this repository** (if you don't have write access)

2. **Choose the appropriate directory** based on the software type:
   - `configurations/marlin/` - For Marlin firmware configs
   - `configurations/klipper/` - For Klipper configs
   - `configurations/prusa/` - For PrusaSlicer profiles
   - `configurations/cura/` - For Cura profiles
   - `configurations/orcaslicer/` - For OrcaSlicer profiles

3. **Create a subdirectory** for your configuration:
   ```bash
   configurations/[software]/[printer-model-or-name]/
   ```

4. **Add your configuration files** to the subdirectory

5. **Create a README.md** in your subdirectory with:
   ```markdown
   # [Printer Model/Configuration Name]
   
   ## Description
   Brief description of this configuration
   
   ## Software Information
   - Software: [Marlin/Klipper/PrusaSlicer/Cura/OrcaSlicer]
   - Version: [Software version]
   - Date: [YYYY-MM-DD]
   
   ## Printer Specifications
   - Model: [Printer model]
   - Hardware Version: [If applicable]
   - Modifications: [List any non-stock modifications]
   
   ## Configuration Details
   - Notable settings or changes
   - Special features enabled/disabled
   - Performance characteristics
   
   ## Installation Instructions
   [Brief instructions on how to use this configuration]
   
   ## Notes
   [Any additional information or warnings]
   
   ## Author
   [Your name or GitHub username]
   ```

6. **Commit your changes** with a descriptive message:
   ```bash
   git add .
   git commit -m "Add [software] configuration for [printer model]"
   ```

7. **Push and create a Pull Request**

### Adding Repository References

1. Open `references/profile-repos.md`

2. Find the appropriate section or create a new one if needed

3. Add your reference following this format:
   ```markdown
   - **[Repository Name](https://github.com/user/repo)** - Brief description of what it contains
   ```

4. Commit and push:
   ```bash
   git commit -m "Add reference to [repository name]"
   ```

### Guidelines

#### For Configuration Files

- **Include complete configurations** - Don't upload partial configurations
- **Test before uploading** - Ensure configurations work as expected
- **Document changes** - If you modified a stock configuration, explain what and why
- **Respect licenses** - Only upload configurations you have permission to share
- **Remove sensitive information** - Remove any WiFi passwords, API keys, etc.

#### For Repository References

- **Verify the link** - Make sure the repository exists and is accessible
- **Check activity** - Prefer actively maintained repositories
- **Brief descriptions** - Keep descriptions to one line
- **Proper categorization** - Place references in the correct section

#### General Guidelines

- **Clear naming** - Use descriptive names for directories and files
- **Consistent formatting** - Follow the existing structure
- **One configuration per PR** - Makes review easier
- **Update documentation** - If adding new categories, update the main README

## File Naming Conventions

### For Marlin Configurations
```
configurations/marlin/[printer-model]/
├── Configuration.h
├── Configuration_adv.h
├── _Bootscreen.h (if custom)
├── _Statusscreen.h (if custom)
└── README.md
```

### For Klipper Configurations
```
configurations/klipper/[printer-model]/
├── printer.cfg
├── macros.cfg (if separate)
├── additional-configs/ (if any)
└── README.md
```

### For Slicer Profiles
```
configurations/[slicer]/[printer-model]/
├── [profile-files]
└── README.md
```

## Version Control Best Practices

- **Meaningful commit messages** - Describe what changed and why
- **One logical change per commit** - Makes history easier to follow
- **Update existing configs** - If updating, explain what changed in the README

## Questions?

If you have questions about contributing:
1. Check existing configurations for examples
2. Open an issue for discussion
3. Review this guide thoroughly

## Code of Conduct

- Be respectful and constructive
- Help others learn and improve
- Give credit where due
- Follow licensing requirements

Thank you for contributing to the community!
