# mrdushidush/scoop-bucket

A [Scoop](https://scoop.sh) bucket for [claudette](https://github.com/mrdushidush/claudette), the air-gapped coding agent in one Rust binary.

```powershell
scoop bucket add mrdushidush https://github.com/mrdushidush/scoop-bucket
scoop install mrdushidush/claudette
```

`claudette.json` updates itself from GitHub releases (`checkver` + `autoupdate`); the hash is the `.sha256` file published with each release.
