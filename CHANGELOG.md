# block-wip-pr-action

## 1.2.0

### Added
- Block all commits that begin with `future!` regardless of whether they're a merge commit.

### Fixed
- Fixed constraint for blocking `fixup!` and `squash!` commits to only match the beginning of the commit message.