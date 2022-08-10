# Base16 Builder Bash

A Bash implementation of a _Base16 Builder_ that follows the guidelines at [Base16](https://github.com/chriskempson/base16).

## Installation

```
git clone https://github.com/mtthlm/base16-builder-bash
```

You'll need to obtain some [scheme files](https://github.com/chriskempson/base16-schemes-source) and [template files](https://github.com/chriskempson/base16-templates) before you can run the Builder.

## Usage

```
cat scheme.yaml | ./base16-builder template.mustache > theme.sh
```
