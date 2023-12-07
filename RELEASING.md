# Release process

- Check if we need to update the CI for newer Go releases
- Check if there is a new LMDB version and update if needed, see `update-lmdb.sh`
- Create a milestone for the version
- Merge all PRs you want to include
- Mark all solved issues and PRs with the milestone for future reference
- Create the release on Github and let it auto-generate the changelog
- Close the milestone
- Create a new PR for this:
  - Copy-paste the changelog into CHANGES.md
  - Update the links in README.md
