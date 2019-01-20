# ![Dourous Logo](assets/logo_dourous_0.png?raw=true)

Download all dourous (lectures) from [dourous.net](https://dourous.net/) using Linux command line.

```
$ download-dourous -h
Usage: download-dourous [OPTS]

    Download all dourous from dourous.net in <out> folder
    if not specified otherwise with -o/--output option

OPTS:
    -o | --output <folder>      Directory that contains dourous
    -h | --help                 Display this help message
```

## Examples

Store dourous in `folder`
```
$ download-dourous -o folder
```

Store dourous in default folder `out`
```
$ download-dourous
```
