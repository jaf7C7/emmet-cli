# A cli wrapper for `emmet`

# Installation

Just clone the repo and symlink the `emmet` script to a directory in your
`PATH`.

## Usage

```
$ emmet 'html:5'
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
