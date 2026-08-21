# Dirloom Scoop bucket

Official Scoop bucket for [Dirloom](https://github.com/dirloom/dirloom).

GitHub Releases is the only artifact source. This bucket never rebuilds Dirloom.

## Install

```powershell
scoop bucket add dirloom https://github.com/dirloom/scoop-bucket
scoop install dirloom
```

Upgrade later releases with:

```powershell
scoop update
scoop update dirloom
```

## Updates

Version bumps are opened as pull requests. Direct pushes to `main` are not used.
Mechanical version PRs need one maintainer approval; workflow changes need two
independent approvals. Every download is verified against the SHA-256 digest of
the official GitHub Release archive.

## License

The bucket metadata is available under the [MIT License](LICENSE).
