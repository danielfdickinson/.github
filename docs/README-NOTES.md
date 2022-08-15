# Notes for the main README.md

## Note 1

Uses [EditorConfig][edconf] for an editor neutral default styling

* Defaults to [using tabs where possible for accessibility
reasons][tabaccess]
* `root = false` so that the user can set their preferred (or required for
accessibility reasons) rendering of the tabs via a `.editorconfig` file in
a higher level directory, or their home directory. Not doing this defeats
the purpose of using tabs vs. spaces.
* `tab_width` is **not** set in this repository so that the user's config
will be used. (See above).

## Note 2

'We' is the 'royal we' (because we don't like saying 'I' a lot and often we
want speak in the first person), and 'I' am
[@danielfdickinson](https://github.com/danielfdickinson).

## Note 3

We use [CSpell][cspell] with [pre-commit][precommit] to catch spelling and other
silly mistakes when committing to this
(<https://github.com/danielfdickinson/.github>) repository.

-------

[cspell]: https://cspell.org
[edconf]: https://editorconfig.org/
[precommit]: https://pre-commit.com
[tabaccess]: https://www.brycewray.com/posts/2022/06/accessibility-argument-tabs-spaces/
