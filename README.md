# goreleaser-playground
Testing out thing for Go Releaser

## Test locally
`goreleaser build --single-target --rm-dist`
`goreleaser release --snapshot --rm-dist`

## Run it for a release
```
export GITHUB_TOKEN="YOUR_GH_TOKEN"
git tag -a v0.y.x -m "First release"
git push origin v0.1.0
goreleaser release
```