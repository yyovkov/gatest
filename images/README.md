# GitHub Actions Tests

## Build only changed directories

### Run Action on Changed Directories only

* GitHub Action [./github/workflows/ci-build-subdir.yml](https://github.com/yyovkov/gatest/blob/master/.github/workflows/ci-build-subdir.yml)

Run this action only if file in one of the subdirectories of _images/**_ has been changed. For example if the file in the directory __images/python/3.95_ have been changed, it will trigger docker build process only for that directory, but will not update the the other versions of _python_ or _datadog-agent_.

