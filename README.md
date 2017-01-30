# My Homebrew Tap

This is an unofficial [Homebrew](http://brew.sh/) [tap](https://github.com/Homebrew/brew/blob/master/docs/How-to-Create-and-Maintain-a-Tap.md).

This tap contains formula created or customized by me,
[pwnall](https://github.com/pwnall/). The formulas are not in official Homebrew
repositories due to rules or disagreements with the maintainers of those
repositories.


## Formula

* [ansible](https://www.ansible.com/) - differs from
  [homebrew-core](https://github.com/Homebrew/homebrew-core/) because their
  formula is [broken](https://github.com/Homebrew/homebrew-core/issues/9337)
* [cudainfo](https://github.com/pwnall/cudainfo) -
  [rejected](https://github.com/Homebrew/homebrew-science/pull/4819) from
  [homebrew-science](https://github.com/Homebrew/homebrew-science/)
* [tensorflow](https://www.tensorflow.org/) - not submitted to
  [homebrew-science](https://github.com/Homebrew/homebrew-science/) due to
  dependency on cudainfo (see above)


## Usage

Install the formula you need directly, as follows.

```bash
brew install pwnall/brews/tensorflow
```

Alternatively, add this tap to your installation.

```bash
brew tap pwnall/brews
brew install tensorflow
```


## Copyright

This is Copyright Homebrew contributors, and distributed under the MIT License.

The unusual copyright clause is due to the fact that the repository contains
modified files from various official Homebrew repositories.
