# setup docker container structure test tool
[![LICENSE](https://img.shields.io/github/license/freenet-actions/setup-container-structure-test)](https://github.com/freenet-actions/setup-container-structure-test/blob/main/LICENSE)

container-structure-test is a command line tool used to test the structure of Docker Images ([see the manual](https://github.com/GoogleContainerTools/container-structure-test)).

This action sets up container-structure-test tool. It downloads the binary from https://github.com/GoogleContainerTools/container-structure-test and adds path to PATH

   
# Usage
## Set up default container structure test version (1.11.0)
```yaml
- uses: freenet-actions/setup-container-structure-test@v2
```
## Set up specific structure test version
```yaml
- uses: freenet-actions/setup-container-structure-test@v2
  with:
    version: 1.11.0
```
