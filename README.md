# goreleaser-playground
Testing out thing for Go Releaser

## Options to test locally
`goreleaser build --single-target --rm-dist`

## Run it for a release
```
export GITHUB_TOKEN="YOUR_GH_TOKEN"
git tag -a v0.y.x -m "release"
git push origin v0.1.0
goreleaser release
```