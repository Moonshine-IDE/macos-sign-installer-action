# macos-sign-installer-action
Sign macOS .pkg installer

| Input |	Description |
| --- | --- |
| unsigned-pkg-path | Path to unsigned .pkg installer |
| signed-pkg-path | Path where the signed .pkg installer will be |
| mac-keychain-pass | Password for keychain |
| mac-installer-certkey | Base64 encoded .p12 certificate and key |
| mac-certkey-pass | Password for .p12 certificate and key |
