# Kubernetes-helm3

A custom brew formulae which will not conflict with existing helm 2 installations. Useful for migrating versions while maintaining compatibility.

You may also want to pin existing helm 2 installations incase the official formulae is updated to helm 3.
`brew pin kubernetes-helm`

## How do I install this formulae?
`brew install gary-mansell/kubernetes-helm3/kubernetes-helm3`

Or `brew tap gary-mansell/kubernetes-helm3` and then `brew install kubernetes-helm3`.

Or install via URL (which will not receive updates):

```
brew install https://raw.githubusercontent.com/Gary-Mansell/homebrew-kubernetes-helm3/master/Formula/kubernetes-helm3.rb
```

## Usage
`helm3 version`

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
