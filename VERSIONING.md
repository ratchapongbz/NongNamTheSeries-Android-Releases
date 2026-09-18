# Release versioning

NongNamTheSeries Android APK releases follow these rules:

1. **Git tag and app version:** use Semantic Versioning as `vMAJOR.MINOR.PATCH`; the APK `versionName` is the same value without the `v` prefix.
2. **Android version code:** use a positive integer that increases for every published APK. It never resets when the semantic major version changes.
3. **Asset names:** publish exactly:
   - `NongNamTheSeries-MAJOR.MINOR.PATCH-arm64.apk`
   - `NongNamTheSeries-MAJOR.MINOR.PATCH-arm64.apk.sha256`
4. **Immutable releases:** never replace an APK attached to an existing tag. A corrected build receives a new patch version and a higher `versionCode`.
5. **Signing continuity:** all updates use the same release signing key and package ID, `com.ratchapongdev.nongnamtheseries`.
6. **Release notes:** record `versionName`, `versionCode`, architecture, minimum/target SDK, SHA-256, verification performed, and known test limitations.

The first release under this scheme is `v1.2.0` with Android `versionCode` 1. The next release must use at least `v1.2.1` and `versionCode` 2.
