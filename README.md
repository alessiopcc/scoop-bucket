# alessiopcc/scoop-bucket

[Scoop](https://scoop.sh) manifests for tools by [@alessiopcc](https://github.com/alessiopcc),
for Windows.

```powershell
scoop bucket add alessiopcc https://github.com/alessiopcc/scoop-bucket
scoop install alessiopcc/glidesh
```

Upgrade with `scoop update glidesh`; remove with `scoop uninstall glidesh` (and
`scoop bucket rm alessiopcc`).

| Manifest | Description |
|---|---|
| [glidesh](https://github.com/alessiopcc/glidesh) | Fast, stateless, SSH-only infrastructure automation |

Manifests install the prebuilt binaries from each project's GitHub release, checked against
its SHA-256. They are updated by each project's release workflow; do not edit them by hand.
