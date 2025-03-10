# _changeme_

\[ **☞☞☞ This is the readme for a project from the
[simple-modern-uv](https://github.com/jlevy/simple-modern-uv) template.** Fill it in and
delete this message!
Below are brief instructions on setup and development workflows that you may use or
modify for your project.
\]

## Installing uv and Python

Sadly, there are many, many ways to install and set up your Python environment, each
with its own pitfalls.

This is a quick cheat sheet for one of the simplest and most reliable ways to set up
**Python+** with [**uv**](https://), the new Python package manager.

For macOS, [brew](https://brew.sh/) is a quick way to install uv:

```shell
brew update
brew install uv
```

For Ubuntu:

```shell
curl -LsSf https://astral.sh/uv/install.sh | sh
```

See [uv's docs](https://docs.astral.sh/uv/getting-started/installation/) for other
platforms and methods.

Now you can install a current Python environment:

```shell
uv python install 3.13 # Or pick another version.
```

## Development

For development workflows, see [development.md](development.md).

* * *

*This project was built from
[simple-modern-uv](https://github.com/jlevy/simple-modern-uv).*
