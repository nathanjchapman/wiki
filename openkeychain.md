# OpenKeychain

## Best Practices for Importing Private Keys from Desktop GPG clients

### Proposed recommendation to new users:

Export your private key to a file.
` $ gpg --export-secret-key ####### --armor > <key.asc>`

Connect your android device via USB.

Transfers key.asc to Android device:
`$ adb push <key.asc> /sdcard/`

Import keys into OpenKeychain.

