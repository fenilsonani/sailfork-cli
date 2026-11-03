# sailfork cli

release binaries for the sailfork command line. the source lives in the main sailfork repo and this repo only holds releases.

install on macOS or Linux (x86_64 and arm64):

```sh
curl -fsSL https://sailfork.com/install | sh
```

it puts `sailfork` in `~/.local/bin` and checks the sha256 of the download. set `SAILFORK_INSTALL_DIR` to pick another folder or `SAILFORK_VERSION=0.1.0` to pin a version. then run `sailfork auth login`.

update later with `sailfork upgrade`.
