# A cli wrapper for `emmet`

## Installation

Just clone the repo, install the dependencies (`emmet`) and symlink the
`emmet` script to a directory in your `PATH`. For example, to install the script
to `~/.local/bin`:

```
git clone https://github.com/jaf7C7/emmet-cli.git && ln -s $PWD/emmet-cli/bin/emmet ~/.local/bin/
```

## Usage

```
$ emmet 'ul>(li>a.my-link$)*5'
<ul>
    <li><a href="" class="my-link1"></a></li>
    <li><a href="" class="my-link2"></a></li>
    <li><a href="" class="my-link3"></a></li>
    <li><a href="" class="my-link4"></a></li>
    <li><a href="" class="my-link5"></a></li>
</ul>
```

Also reads from stdin:
```
$ echo \! | emmet
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
	
</body>
</html>
```

## TODO:

Add command-line options:

- [ ] Stylesheets: `-s`
- [ ] Markup: `-m` (the default)
- [ ] Indentation type: `-i <string>` e.g. `-i '\t'`, `-i '    '`
