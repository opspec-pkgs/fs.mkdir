# Problem statement
creates a directory

# Example usage

> note: in examples, VERSION represents a version of the fs.mkdir pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/fs.mkdir#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/fs.mkdir#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/fs.mkdir#VERSION }
  outputs: 
    dir:
```


# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/fs.mkdir/issues)
