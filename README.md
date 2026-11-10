# strace

strace 7.3: shows the system calls a program makes (needs ptrace)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install strace
```

| | |
|---|---|
| Version | 7.3 |
| Licence | LGPL-2.1-or-later |
| Upstream | https://strace.io |
| Needs | none |
| Needs tOS build | 627 or newer |
| Size | 1093160 bytes (2743424 unpacked) |
| SHA-256 of the `.tpkg` | `c45999c108df7e17cd314ad3555e3645094b323ff75de79d5596ff4e5cce3cfa` |

## Commands it adds

| Command | Runs |
|---|---|
| `strace` | `bin/strace` |

## Download

The package file (`strace-7.3.tpkg`) and the sources it was built from are the assets of the
[v7.3 release](https://github.com/Artfical/tpkg-strace/releases/tag/v7.3).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `strace-7.3.tar.xz`

Check a download: `sha256sum strace-7.3.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: LGPL-2.1-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
