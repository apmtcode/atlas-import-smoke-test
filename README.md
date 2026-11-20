# Atlas creator import test fixture

This repository is a deliberately small fixture for verifying GitHub sign-in, repository ownership checks, import processing, and owner-visible pending listings in Atlas staging.

It contains one standalone skill and one metadata-only Claude plugin. It is not a production capability. Neither package contains executable scripts, external network calls, secrets, or dependencies. No existing project code is included.

Expected import: two pending listings, each pinned to the imported commit and inheriting the root MIT license. Do not approve these fixtures for public discovery, build downloadable artifacts, install them, or enable spending as part of the creator-import test.

## Files

- `skills/atlas-import-verification/SKILL.md`: minimal skill source.
- `plugins/atlas-import-fixture/.claude-plugin/plugin.json`: metadata-only plugin manifest.
- `LICENSE`: the full MIT grant for this fixture.

Publishing this fixture repository is a separate user-approved step. Import alone does not enable a paid installation.
