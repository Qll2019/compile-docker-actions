# Compilation docker action

This action prints "Compile main.c" or "Compile" + the name of a file to be compiled to the log.

## Inputs

### `what-to-compile`

**Required** The name of the file to be compiled. Default `"main.c"`.

## Outputs

### `time`

The completion time of compilation.

## Example usage

uses: Qll2019/compile-docker-actions/compile-action@v1
with:
  what-to-compile: 'Source Code'
