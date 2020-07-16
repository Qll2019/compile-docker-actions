# Pre-build docker action

This action prints "Pre-build files" or "Pre-build" + the name of a file to be pre-builded to the log.

## Inputs

### `what-to-pre-build`

**Required** The name of the file to be compiled. Default `"files"`.

## Outputs

### `time`

The completion time of compilation.

## Example usage

uses: Qll2019/compile-docker-actions/prebuild-action@v1
with:
  what-to-pre-build: 'Source Code'
