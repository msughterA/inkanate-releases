# Inkanate releases

Built installers for [Inkanate](https://inkanate.com). Every download the
website offers is an asset on a release here.

Nothing is committed to this repository by hand — it exists to hold release
assets, and this file exists because a GitHub release needs a tag, and a tag
needs a commit.

- **Linux and Windows** are built and uploaded by `release.yml` in the
  `inkanate` repository.
- **macOS** is built on a Mac and uploaded with `dev/osx/publish-mac-release.sh`,
  because a macOS runner bills at ten times the Linux rate.

Release metadata is POSTed to the Inkanate backend, which is what the download
page reads; the installers themselves are served from here.
