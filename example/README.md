# example

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] example`
Details: https://kpt.dev/reference/pkg/get/

### View package content
`kpt pkg tree example`
Details: https://kpt.dev/reference/pkg/tree/

### Apply the package
```
kpt live init example
kpt live apply example --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/live/
