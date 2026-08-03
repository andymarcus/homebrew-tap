# andymarcus/tap

Homebrew formulae for [Andy Marcus](https://github.com/andymarcus)'s tools.

## Formulae

| Formula | Description |
| --- | --- |
| [`filetree`](https://github.com/andymarcus/filetree-cli) | Interactive, colour-coded file-tree browser for your terminal |

## Install

```bash
brew install andymarcus/tap/filetree
```

There's no separate `brew tap` step — the `user/tap/formula` form taps on the
fly. Or, in a `brew bundle` `Brewfile`:

```ruby
tap "andymarcus/tap"
brew "filetree"
```

## Notes

These formulae build from source on install — no bottles are published yet.
The Python-based ones are quick, since they just create a virtualenv and
install pinned dependencies, but expect a one-off Python download if you don't
already have Homebrew's `python@3.14`.

## Documentation

`brew help`, `man brew`, or [Homebrew's documentation](https://docs.brew.sh).
