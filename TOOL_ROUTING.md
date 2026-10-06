# Project Status Widget Releases Tool Routing

Inherit: `Kayus24/vibe-shared-knowledge/tool-routing/BASELINE.md`.

## Source of truth
1. Published release metadata/assets in this repository
2. Source code in `Kayus24/project-status-widget`
3. Canonical signing identity in the source repository

## Preferred hierarchy
- Release repo state/assets: **GitHub**
- APK hash/signature verification before publishing: **Remote Desktop Commander / Android build tools**
- Source bugs: return to `Kayus24/project-status-widget`

## Avoid
Do not use this repository for source-code fixes, design work, browser automation, research or generated assets.

## Gates
- Publish only artifacts built/tested from the source repo.
- Verify SHA-256 and canonical signer before release metadata is changed.
