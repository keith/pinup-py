# pinup

This is a replacement for
[pinup](https://github.com/Keithbsmiley/pinup). It only does one simple
thing. It opens unread or untagged pins from
[pinboard](https://pinboard.in) in the browser.

## Usage

```
pinup 5
```

This opens the 5 most recent untagged and unread posts, the deletes them
from pinboard.

To do this you must set your pinboard credentials in your `~/.netrc`
file. You must use your API token for this which you can find
[here](https://pinboard.in/settings/password). The `login` and
`password` fields correspond to the first and second half of the token,
split by the `:`, respectively.

```
machine pinboard.in
  login USERNAME
  password TOKEN
```

## Install

Install with homebrew:

```
brew tap Keithbsmiley/formulae
brew install pinup
```
