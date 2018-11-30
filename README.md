# Parse a json file to a json Tree

Add support for Floats to zig/std/json\*. Since zig cannot
yet parse Floats I've created this standalone module and
using the ParseNumber module.

## Dependencies

* [zig](https://ziglang.org)
* [zig-json](https://github.com/winksaville/zig-json)

## Use

To clone this repo use `git clone --recursive` as git submodules are used.

```bash
git clone --recursive https://github.com/winksaville/zig-parse-json-file.git path.to.zig-parse-json-file
```

## Test
```bash
$ zig test parse-json-file.zig
```

## Clean
Remove `zig-cache/` directory
```bash
$ rm -rf ./zig-cache/
```
