This script automates the process of cloning a Git repository, building a package using `makepkg`, and cleaning up temporary files. It is particularly useful for Arch Linux users who frequently build packages from source.

## Usage

1. Save the script to a file, for example `build_package.sh`.
2. Make the script executable:
   ```bash
   chmod +x build_package.sh
   ```
3. Run the script:
   ```bash
   ./build_package.sh
   ```
4. When prompted, enter the Git repository URL you want to clone and build.
