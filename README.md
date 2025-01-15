## Zig: what, how and why

[Event]() | [Slides](https://docs.google.com/presentation/d/14lR4fRUT46wLplrwlexLECpB1lPOpuBvTNsSm7fMq30/edit?usp=sharing)

This project uses [Zig 0.13](https://ziglang.org/download/#release-0\.13\.0)

### Run the tests

To execute the tests seen during the talk:

```shell
zig build test
```

or:

```shell
zig test src/syntax.zig
zig test src/comptime.zig
```

It is possible to compile and run tests in isolation by adding the `--test-filter=<test-pattern>` flag, for example:

```shell
zig build test --  "defer"
```

or:


```shell
zig test syntax.zig --test-filter=defer
```

### Build the project

```shell
zig build
```
