# 0.2.4 (Wed Oct 19 2022)

#### 🏠 Internal

- Update GitHub Actions action versions [#67](https://github.com/datalad/datalad-deprecated/pull/67) ([@jwodder](https://github.com/jwodder))

#### 🧪 Tests

- "Fix" one failing test and improve their "infrastructure" [#70](https://github.com/datalad/datalad-deprecated/pull/70) ([@yarikoptic](https://github.com/yarikoptic))

#### Authors: 2

- John T. Wodder II ([@jwodder](https://github.com/jwodder))
- Yaroslav Halchenko ([@yarikoptic](https://github.com/yarikoptic))

---

# 0.2.3 (Fri Sep 30 2022)

#### 🐛 Bug Fix

- Remove last traces of `datalad.metadata` [#65](https://github.com/datalad/datalad-deprecated/pull/65) ([@christian-monch](https://github.com/christian-monch))
- Add metadata code that is removed from core [#63](https://github.com/datalad/datalad-deprecated/pull/63) ([@christian-monch](https://github.com/christian-monch) [@mih](https://github.com/mih))
- BF: do not install devel datalad (pytest-ed now) for devel -- released is ok now [#60](https://github.com/datalad/datalad-deprecated/pull/60) ([@yarikoptic](https://github.com/yarikoptic))

#### ⚠️ Pushed to `master`

- DOC: Set language in Sphinx config to en ([@adswa](https://github.com/adswa))

#### 🧪 Tests

- RF: migrate from using nose for testing to pytest [#51](https://github.com/datalad/datalad-deprecated/pull/51) ([@yarikoptic](https://github.com/yarikoptic))
- Update Appveyor config to use new codecov uploader [#58](https://github.com/datalad/datalad-deprecated/pull/58) ([@jwodder](https://github.com/jwodder))

#### Authors: 5

- Adina Wagner ([@adswa](https://github.com/adswa))
- Christian Mönch ([@christian-monch](https://github.com/christian-monch))
- John T. Wodder II ([@jwodder](https://github.com/jwodder))
- Michael Hanke ([@mih](https://github.com/mih))
- Yaroslav Halchenko ([@yarikoptic](https://github.com/yarikoptic))

---

# 0.2.2 (Mon May 02 2022)

#### 🏠 Internal

- Update build setup to include needed files [#57](https://github.com/datalad/datalad-deprecated/pull/57) ([@yarikoptic](https://github.com/yarikoptic))

#### Authors: 1

- Yaroslav Halchenko ([@yarikoptic](https://github.com/yarikoptic))

---

# 0.2.1 (Fri Apr 29 2022)

#### 📝 Documentation

- Add other added commands (diff, annotate-paths, publish) to README.md [#55](https://github.com/datalad/datalad-deprecated/pull/55) ([@yarikoptic](https://github.com/yarikoptic))

#### Authors: 1

- Yaroslav Halchenko ([@yarikoptic](https://github.com/yarikoptic))

---

# 0.2.0 (Fri Apr 29 2022)

#### 🚀 Enhancement

- RF: datalad_deprecated -> datalad.deprecated for sibling_webui [#50](https://github.com/datalad/datalad-deprecated/pull/50) ([@yarikoptic](https://github.com/yarikoptic))
- Import AnnotatePaths [#46](https://github.com/datalad/datalad-deprecated/pull/46) ([@mih](https://github.com/mih))
- Import deprecated GitRepo.*_submodule() methods [#38](https://github.com/datalad/datalad-deprecated/pull/38) ([@mih](https://github.com/mih))
- Adding context menu and rendering options for certain files [#27](https://github.com/datalad/datalad-deprecated/pull/27) ([@dereklu888](https://github.com/dereklu888))
- Import the `publish()` command from -core [#28](https://github.com/datalad/datalad-deprecated/pull/28) ([@mih](https://github.com/mih))
- Added links to the names of directories and files [#26](https://github.com/datalad/datalad-deprecated/pull/26) ([@dereklu888](https://github.com/dereklu888))
- Add COPYING from main codebase (tuned) [#25](https://github.com/datalad/datalad-deprecated/pull/25) ([@yarikoptic](https://github.com/yarikoptic))
- Add release badges [#25](https://github.com/datalad/datalad-deprecated/pull/25) ([@mih](https://github.com/mih))

#### 🐛 Bug Fix

- Made context menu button always visible [#36](https://github.com/datalad/datalad-deprecated/pull/36) ([@dereklu888](https://github.com/dereklu888))
- Web UI title change [#30](https://github.com/datalad/datalad-deprecated/pull/30) ([@dereklu888](https://github.com/dereklu888))

#### ⚠️ Pushed to `master`

- Fixup import to internal `diff` ([@mih](https://github.com/mih))

#### 🏠 Internal

- Set up auto [#54](https://github.com/datalad/datalad-deprecated/pull/54) ([@jwodder](https://github.com/jwodder))

#### 📝 Documentation

- just reference that there is a dedicated webui [#52](https://github.com/datalad/datalad-deprecated/pull/52) ([@yarikoptic](https://github.com/yarikoptic))

#### Authors: 4

- Derek ([@dereklu888](https://github.com/dereklu888))
- John T. Wodder II ([@jwodder](https://github.com/jwodder))
- Michael Hanke ([@mih](https://github.com/mih))
- Yaroslav Halchenko ([@yarikoptic](https://github.com/yarikoptic))
