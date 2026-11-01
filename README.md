# Still provisioning

Public download location for the permanently signed Still Android provisioning APK.

The repository contains no signing keys, passwords, policy keys, or user data.

## Current provisioning release

- APK: `Still-0.1.4-android17.apk`
- SHA-256: `E646462066C4E1F902FE27ACB005C9F95CFD4FF5598E256D55A19D3A1090246F`
- Signing certificate SHA-256: `17B619D0C418732F8703AA3328EEB8377262963923F973D50A370C55CA97FAD1`

Version 0.1.4 includes the Android 12–17 provisioning callbacks, the real-app Still launcher, transactional policy application and rollback, and quarantine for newly installed unapproved apps. It also allows Setup Wizard to finish before verifying that Still resolves as Home, fixing the physical-device compliance loop in 0.1.3. Development pause remains enabled for physical-device testing. Older APKs are retained only as release history and should not be used for provisioning.
