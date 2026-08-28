# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| v4.4 (latest) | ✅ |
| < v4.0 | ❌ |

## Reporting a Vulnerability

If you discover a security vulnerability, **do not open a public issue**.

Contact the maintainer directly via the contact listed on the GitHub profile.  
Include a clear reproduction path and any relevant logs or proof-of-concept.

You will receive a response within **72 hours**.

## Release Verification

All release binaries are verified by SHA-256 checksum, published in the README table.  
Always verify the hash before executing any downloaded file.

```powershell
Get-FileHash .\DonutFlipSetup.exe -Algorithm SHA256
```

Compare the output against the hash listed in [README.md](README.md).
