# dot2svg

[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run)

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
