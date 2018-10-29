# pyarnold

Python implementation of [ArnoldC](https://github.com/lhartikk/ArnoldC)


## Installation

`pip install pyarnold`

## Example

**HelloWorld.arnoldc**

```ArnoldC
IT'S SHOWTIME
TALK TO THE HAND "hello world"
YOU HAVE BEEN TERMINATED
```

## Usage

```bash
$ pyarnold examples/HelloWorld.arnoldc
$ pyarnold --example
IT'S SHOWTIME
TALK TO THE HAND "Hello World!"
YOU HAVE BEEN TERMINATED
$ pyarnold --example | pyarnold
$ pyarnold -c <<EOF
> IT'S SHOWTIME
> TALK TO THE HAND "Hello World!"
> YOU HAVE BEEN TERMINATED
> EOF
Hello World!
```

## Language Documentation

[Official ArnoldC documentation](https://github.com/lhartikk/ArnoldC/wiki/ArnoldC)
