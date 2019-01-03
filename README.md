# oanhnn/docker-aws-workbench

[![Software License](https://img.shields.io/github/license/oanhnn/docker-aws-workbench.svg)](LICENSE)
[![Build Status](https://img.shields.io/travis/oanhnn/docker-aws-workbench/master.svg)](https://travis-ci.org/oanhnn/docker-aws-workbench)
[![Docker Build Method](https://img.shields.io/docker/automated/oanhnn/aws-workbench.svg)](https://hub.docker.com/r/oanhnn/aws-workbench)
[![Docker Build Status](https://img.shields.io/docker/build/oanhnn/aws-workbench.svg)](https://hub.docker.com/r/oanhnn/aws-workbench)
[![Docker Pull Counter](https://img.shields.io/docker/pulls/oanhnn/aws-workbench.svg)](https://hub.docker.com/r/oanhnn/aws-workbench)
[![Docker Star Counter](https://img.shields.io/docker/stars/oanhnn/aws-workbench.svg)](https://hub.docker.com/r/oanhnn/aws-workbench)

Repository of `oanhnn/aws-workbench` Docker image.

## Tags

### Version tags

Image Tag    | Base Image           | Badges
-------------|----------------------|-------

### Shared tags

- `latest`

## Features

- [x] Base from `alpine:3.8` image
- [x] Install `awscli`, `awsebcli`, `s3cmd`
- [x] Install `terraform`
- [x] Install some utility packages: `jq`, `less`

## Requirement
- Docker Engine 1.13+

## Usage

```bash
$ docker run --rm -it -v $(pwd):/app oanhnn/aws-workbench:tag sh
```

You can use environment variables to specify configuration options and credentials. See [more](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-envvars.html)

## Contributing

All code contributions must go through a pull request and approved by a core developer before being merged. 
This is to ensure proper review of all the code.

Fork the project, create a feature branch, and send a pull request.

If you would like to help take a look at the [list of issues](https://github.com/oanhnn/docker-aws-workbench/issues).

## License

This project is released under the MIT License.   
Copyright © 2018-2019 [Oanh Nguyen](https://github.com/oanhnn)   
Please see [License File](https://github.com/oanhnn/docker-aws-workbench/blob/master/LICENSE) for more information.
