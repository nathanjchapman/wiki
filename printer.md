# Printers (CUPS)

## How to setup a printer

Source: https://wiki.voidlinux.eu/CUPS

`$ xbps-install cups cups-filters`

If you have a hp printer and need hp drivers you should install hplip:
`$ xbps-install hplip`

### Starting the CUPS server
Be sure to enable and start the service before trying to use it.
`$ ln -s /etc/sv/cupsd /var/service/`

In a browser go to: `localhost:631`

### Configure CUPS
There are many different applications which can be used to configure CUPS. If you prefer a GUI tool: perhaps your desktop manager has an application to do this, or install system-config-printer:
`$ sudo xbps-install system-config-printer`

