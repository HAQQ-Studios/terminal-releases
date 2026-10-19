# HAQQ Terminal releases

App builds offered inside HAQQ Terminal. The apps read `update.json` and offer a build whose number is higher than their own.

- **Android:** each release here holds a signed APK. `update.json` names it with its SHA-256.
- **iPhone:** builds go through TestFlight. `update.json` points at the TestFlight invite.

Nothing here is on the terminal's server, so publishing a build never touches the terminal. A build is published only when someone runs the release scripts in `HAQQ-Studios/mev-terminal` (`apps/scripts/`).
