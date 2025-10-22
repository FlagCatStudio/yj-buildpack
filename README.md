# yj-buildpack

A tiny buildpack that download the `yj` utility to an image.

The `yj` utility will be available during *build* and *launch*

## Usage

Add the following lines to your `project.toml` file:

``` toml
[[io.buildpacks.group]]
  uri = "ghcr.io/flagcatstudio/buildpacks/github.com_flagcatstudio_yj-buildpack:0.0.1"
```
