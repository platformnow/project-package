# PlatformNOW Project Package

The project package provides crossplane compositions to install a project.


## Installation

```bash
kubectl apply -f packages/package.yaml
```
## Usage

Now you can apply the desired XR. For example, to install a project with the default values

```bash
kubectl apply -f defaults/project.yaml
```
Examples of other XR's can be found in the [examples](examples) folder.

## Publishing

Github Actions is used to build and publish the package. The following steps can be performed:

1. Create a tag

```bash 
git tag v0.0.1 -m "Release v0.0.1"
```

2. Push the tag

```bash
git push --tags
```
