# MT::Tool::Launcher

## NAME

MT::Tool::Launcher - The launcher of admin screen menus.

## USAGE

```sh
$ cd $MT_HOME && ./tools/launcher --protocol=https --host=cms.example.com
```

### EXAMPLE

#### ex1) Open a create entry screen of a website.

![Screenshot1](https://github.com/taiju/mt-tool-launcher/raw/master/artwork/launcher1.gif)

#### ex2) Open plugin setting screens of all websites and blogs.

![Screenshot2](https://github.com/taiju/mt-tool-launcher/raw/master/artwork/launcher2.gif)

## OPTIONS

### --protocol=PROTOCOL

Set the protocol of admin screen url.

Default is `http`.

### --host=HOST

Set the host of admin screen url.

Default is `localhost`.

### --cmd=PATH

Set the peco (or percol) command path. (default: auto)

## REQUIREMENTS

### COMMANDS

[peco](https://github.com/peco/peco) or [percol](https://github.com/mooz/percol)

### PERL MODULES

[File::Which](https://metacpan.org/pod/File::Which)

## INSTALLING

1. Unpack the mt-tool-launcher archive.
2. Upload and copy the mt-tool-launcher/tools/launcher to your MT's tools folder. ( /path/to/mt/tools )

## LICENSE

The MIT License (MIT)

## COPYRIGHT

taiju \<higashi@taiju.info\>
