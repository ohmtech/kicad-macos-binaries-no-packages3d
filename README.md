# kicad-macos-binaries-no-packages3d

This repository contains KiCad macOS binaries dependency to speed-up ERB CI.

compared to the KiCad `apt` package, the Brew Cask package will contain all 3d packages
for all modules. This represents nearly 5GB of data.

By removing it from the install, we can run faster on CI, to match Linux build time.
