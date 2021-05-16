# setters-example

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] setters-example`
Details: https://kpt.dev/reference/pkg/get/

### View package content
`kpt pkg tree setters-example`
Details: https://kpt.dev/reference/pkg/tree/

### Apply the package
```
kpt live init setters-example
kpt live apply setters-example --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/live/
