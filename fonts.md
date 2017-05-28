# Fonts

## Adding Fonts to Fontconfig

Adding new fonts to the Fontconfig subsystem is a straightforward process.

1. To add fonts system-wide, copy the new fonts into the `/usr/share/fonts/` directory. It is a good idea to create a new subdirectory, such as `local/` or similar, to help distinguish between user-installed and default fonts. To add fonts for an individual user, copy the new fonts into the `.fonts/` directory in the user's home directory.

2. Use the `fc-cache` command to update the font information cache, as in the following example:
`fc-cache <path-to-font-directory>`. In this command, replace `<path-to-font-directory>` with the directory containing the new fonts (either `/usr/share/fonts/local/` or `/home/<user>/.fonts/`).

