# Wavemaker CLI

Signed releases of `wavemaker`, the command-line client for [Wavemaker](https://wavemaker.io).

Install instructions for your platform are at **https://wavemaker.io/download**.

- Every release is tagged `cli-v<version>` and is immutable: its files are never replaced.
- Each archive has a `.sha256` sidecar, and the release attests every file. Check a
  download with `gh release verify-asset <downloaded file> -R AdwaveInc/wavemaker`.
- Update an installed client with `wavemaker self update`.

The source code is not published here. This repository holds release files only, so
issues are off; for help, see https://wavemaker.io/help. Report security problems to
security@adwave.com.

Copyright (c) 2026 Adwave Digital Inc. See [LICENSE](LICENSE).
