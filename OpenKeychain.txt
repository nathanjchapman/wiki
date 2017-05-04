# Best Practices for Importing Private Keys from Desktop GPG clients

Proposed recommendation to new users:

Export your private key to a fille.
Mailvelope: Export all keys -> keys.asc
gpg: gpg --export-secret-key ####### --armor > keys.asc
Connect your android device via USB
Transfers keys.asc to Android device
