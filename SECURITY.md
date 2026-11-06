# Security and signing

The release signing key is not included in Git history, source archives or release assets. Do not upload it to an issue or commit it to the repository.

The published exp5 APK certificate SHA-256 is:

`68d34f094ffba5b3499dffef80ee36bc8c25b8b44b4bffe3eda59f1fc45a13bf`

Local builds create their own test keys. CI uses an ephemeral test key; its artifacts cannot update the published APK and are not promoted to releases automatically.

The APK requests no Internet permission. Configuration writes are restricted to the module app and platform-signed Settings. The optional Restart scopes button invokes root only after the user taps it and confirms the prompt.

Public issue reports should not include private framework dumps, notifications, account information, credentials or signing material. For a sensitive report, contact the repository maintainer before posting details publicly.
