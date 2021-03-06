# Kirshenbaum ASCII-IPA to Unicode translator

Forked from https://github.com/coruus/ascii-ipa

Reads from STDIN and writes to STDOUT when run directly with:

```
python kirshenbaum.py
```

You can pipe in and write out

```
python kirshenbaum.py < kirshenbaum.txt > ipa.txt
```

Default is a Kirshenbaum -> IPA conversion, but it can easily do conversion both
ways, just edit the main function

An inefficient and ugly Python translator from the `sci.lang` and
`alt.usage.english` ASCII IPA format (as standardized by Evan
Kirshenbaum) and Unicode IPA glyphs.

It works well enough; pull requests happily accepted.

(As it happens, ASCII IPA is fairly convenient to enter on modern
touch devices. A link to a Gist for Pythonista is likely.)

[Evan Kirshenbaum][kirshipa] maintains the [specification][KPDF], as well
as a guide to its use. (But, for the moment, note the erratum found in
this repo's [docs/errata.markdown][errata].)

[kirshipa]: http://www.kirshenbaum.net/IPA/
[KPDF]: http://www.kirshenbaum.net/IPA/ascii-ipa.pdf
[errata]: https://github.com/coruus/ascii-ipa/blob/master/docs/errata.markdown
