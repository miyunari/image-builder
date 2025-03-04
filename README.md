Image Builder
=============

Image Builder serves as an HTTP API on top of [Osbuild
Composer](https://github.com/osbuild/osbuild-composer), and serves as the
backend for [Image Builder
Frontend](https://github.com/osbuild/image-builder-frontend/).

Image Builder is intended to be run within the
[console.redhat.com](https://console.redhat.com) platform.

### OpenAPI spec

The [latest api
specification](https://github.com/osbuild/image-builder/blob/main/internal/v1/api.yaml).

### Updating package lists

`tools/generate-package-lists` can be used in combination with a `distributions/`
file to generate a package list.

If the repository requires a client tls key/cert you can supply them with
`--key` and `--cert`.

### Contributing

Please refer to the [developer guide](https://www.osbuild.org/guides/developer-guide/developer-guide.html) to learn about our workflow, code style and more.