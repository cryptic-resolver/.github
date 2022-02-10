# Cryptic Resolver

![screenshot](./screenshot.png)

<div align="center">

| **cr in Ruby** | **cr in D**  | **cr in Go** |
|:------------:|:---------:|:-----------:|
| [![Gem Version](https://badge.fury.io/rb/cryptic-resolver.svg)](https://rubygems.org/gems/cryptic-resolver)  | [![GitHub version](https://badge.fury.io/gh/cryptic-resolver%2Fcr_D.svg)][cr_D] | [![GitHub version](https://badge.fury.io/gh/cryptic-resolver%2Fcr_Go.svg)][cr_Go] |

</div>


<br>

## Install

Ruby versiond `cr` is the reference implementation, always up-to-date.
```bash
gem install cryptic-resolver
```

<br>

We provide pre-built binaries for `cr` as well via [cr_D] and [cr_Go]

**For Windows user**
```powershell
# D version (smaller size)
scoop install "https://raw.githubusercontent.com/cryptic-resolver/cr_D/main/install/cryptic-resolver.json"

# Go version
scoop install "https://raw.githubusercontent.com/cryptic-resolver/cr_Go/main/install/cryptic-resolver.json"
```


**For Linux user**
```bash
# D version
bash -c "$(curl -fsSL https://raw.githubusercontent.com/cryptic-resolver/cr_D/main/install/i.sh)"

# Go version (smaller size)
bash -c "$(curl -fsSL https://raw.githubusercontent.com/cryptic-resolver/cr_Go/main/install/i.sh)"
```


**For macOS user**
```bash
# only Go version
bash -c "$(curl -fsSL https://raw.githubusercontent.com/cryptic-resolver/cr_Go/master/install/i.sh)"
```

[cr_Go]: https://github.com/cryptic-resolver/cr_Go
[cr_D]: https://github.com/cryptic-resolver/cr_D
