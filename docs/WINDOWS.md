# BlockX for Windows

Download the **BlockX-Windows** artifact from the latest successful GitHub Actions run under Actions > Windows EXE. Extract the artifact and run the installer or portable EXE. Windows SmartScreen may warn because the early alpha is unsigned.

To build locally, install Node.js 22+, then run `npm install` and `npm run dist:win`. Executables appear in `release/`.

Note: GitHub Actions must be enabled for the repository. This workflow generates builds; it does not automatically publish a GitHub Release.
