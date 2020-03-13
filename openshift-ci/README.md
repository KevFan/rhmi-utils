## OpenShift CI

### Dockerfile.tools

Base image used on CI for all builds and test jobs. See [here](https://github.com/integr8ly/ci-cd/blob/master/openshift-ci/README.md) for more information on creating and deploying a new image.

#### Build and Test

```
$ docker build -t registry.svc.ci.openshift.org/integr8ly/rhmi-utils-base-image:latest - < Dockerfile.tools
$ IMAGE_NAME=registry.svc.ci.openshift.org/integr8ly/rhmi-utils-base-image:latest test/run
ShellCheck - shell script analysis tool
version: 0.3.8
license: GNU General Public License, version 3
website: http://www.shellcheck.net
SUCCESS!
```