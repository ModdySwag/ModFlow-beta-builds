# ModFlow OrderFlow Analysis Suite — beta builds

Beta binaries for ModFlow OrderFlow Analysis Suite: the installer, the portable build and the
SBOM for each release.

The source, the docs and every receipt live in the main repository:
[ModdySwag/ModFlow-OrderFlow-Analysis-Suite](https://github.com/ModdySwag/ModFlow-OrderFlow-Analysis-Suite).

## What is here

Each release carries three files:

- `ModFlowOrderFlowAnalysisSuite-Setup-0.1.0.exe` — the installer. Per-user, no admin prompt,
  desktop shortcut, plain uninstall from Add/Remove.
- `ModFlowOrderFlowAnalysisSuite-win64.zip` — the portable build: unzip anywhere, run the exe.
- `ModFlowOrderFlowAnalysisSuite-win64.sbom.cdx.json` — the CycloneDX software bill of materials
  for the exact dependency set inside the build.

Release notes carry the sha256 of every file — check what you downloaded.

Feedback and issues: through the main repository above.

## Code signing policy

**Free code signing provided by [SignPath.io](https://signpath.io/), certificate by
[SignPath Foundation](https://signpath.org/).**

These binaries are built by the main repository's CI, and the same pipeline signs them: the
application and the installer go to SignPath in one signing request, and every signed file is
re-verified before a release is published. Releases published before the Foundation onboarding
completes ship unsigned — each release's notes say which files are signed.

**Team roles.** One maintainer holds every role:

| Foundation role | Member |
| --- | --- |
| Committers and reviewers | [@ModdySwag](https://github.com/ModdySwag) |
| Approvers | [@ModdySwag](https://github.com/ModdySwag) |

**Privacy policy:** this program will not transfer any information to other networked systems unless
specifically requested by the user or the person installing or operating it. The main repository's
[Code signing policy](https://github.com/ModdySwag/ModFlow-OrderFlow-Analysis-Suite#code-signing-policy)
section lists the complete set of outbound calls.
