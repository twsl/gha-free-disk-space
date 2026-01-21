# Github Actions Free Disk Space

A fast, configurable GitHub Action to free up disk space on GitHub Actions runners. 

```yml
  - name: Free Disk Space
    uses: twsl/gha-free-disk-space@v1
    with:
      dotnet: "true"
      haskell: "true"
      swap-storage: "true"
```
