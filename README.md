# dot2svg

[![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.svg)](https://console.cloud.google.com/cloudshell/editor?shellonly=true&cloudshell_image=gcr.io/cloudrun/button&cloudshell_git_repo=https://github.com/broady/dot2svg.git)

A web server that converts dot files to svg.

```bash
function dot2svg {
    curl -s --data-binary @$1 https://dot2svg-cgojka5t4a-uc.a.run.app/dot2svg > ${1%.dot}.svg;
}
```

## Support

Not an official Google product.

## License

Code in this repository is licensed under the Apache 2.0. See [LICENSE](LICENSE).